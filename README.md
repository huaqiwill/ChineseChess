# 中国象棋游戏

这是一个基于Python和Pygame实现的中国象棋游戏。

## 功能特点
- 支持双人对战模式
- 电脑AI对战功能
- 重新开始游戏按钮
- 标准中国象棋规则实现

## 项目结构
- `main.py`: 主游戏逻辑和界面
- `app/button.py`: 按钮控件实现
- `app/computer.py`: 电脑AI逻辑
- `app/constants.py`: 游戏常量和配置
- `app/pieces.py`: 所有棋子类和移动规则
- `resource/`: 棋子图片资源

## 运行要求
- Python 3.x
- Pygame库

## 安装与运行
1. 安装依赖:
```
pip install pygame
```
2. 运行游戏:
```
python main.py
```

## 游戏控制
- 鼠标点击选择棋子
- 点击目标位置移动棋子
- 点击"重新开始"按钮重置游戏

## 开发说明
游戏实现了中国象棋所有棋子的标准移动规则，包括:
- 车(Rooks)的直线移动
- 马(Knighs)的日字移动
- 象(Elephants)的田字移动
- 士(Mandarins)的斜线移动
- 将(King)的一步移动
- 炮(Cannons)的隔山打牛
- 兵(Pawns)的前进和过河后的左右移动"# ChineseChess" 
