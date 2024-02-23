# MDP REPRESENTATION
## AIM:
To represent any one real world problem in Markov Decision Problem(MDP).

## PROBLEM STATEMENT:
### Problem Description
Move the snake 🐍 to reach the apple 🍏, which is the goal in a 3*3 grid.

### State Space
{0,1,2,3,4,5,6,7,8} 

### Sample State
2

### Action Space
{Up[0],Down[1],Left[2],Right[3]}

### Sample Action
Down[1]

### Reward Function
R = { +1 , if the snake eats the apple
       0 , otherwise

### Graphical Representation
![WhatsApp Image 2023-09-11 at 08 19 41](https://github.com/KeerthikaNagarajan/mdp-representation/assets/93427089/ad75129c-91bf-4750-a736-81ad3ddb6952)


## PYTHON REPRESENTATION:
```python
# Creating Dictionary
P={
    0:{
        0:[(0.666,0,0.0,False),(0.333,3,0.0,False)],
        1:[(0.333,3,0.0,False),(0.333,0,0.0,False),(0.333,1,0.0,False)],
        2:[(0.666,0,0.0,False),(0.333,3,0.0,False)],
        3:[(0.333,1,0.0,False),(0.333,0,0.0,False),(0.333,3,0.0,False)]
    },
    1:{
        0:[(0.333,1,0.0,False),(0.333,0,0.0,False),(0.333,2,0.0,False)],
        1:[(0.333,4,0.0,False),(0.333,0,0.0,False),(0.333,2,0.0,False)],
        2:[(0.333,0,0.0,False),(0.333,1,0.0,False),(0.333,4,0.0,False)],
        3:[(0.333,2,0.0,False),(0.333,1,0.0,False),(0.333,4,0.0,False)]
    },
    2:{
        0:[(0.666,2,0.0,False),(0.333,1,0.0,False)],
        1:[(0.333,5,0.0,False),(0.333,1,0.0,False),(0.333,2,0.0,False)],
        2:[(0.333,1,0.0,False),(0.333,2,0.0,False),(0.333,5,0.0,False)],
        3:[(0.666,2,0.0,False),(0.333,5,0.0,False)]
    },
    3:{
        0:[(0.333,0,0.0,False),(0.333,3,0.0,False),(0.333,4,0.0,False)],
        1:[(0.333,6,0.0,False),(0.333,3,0.0,False),(0.333,4,0.0,False)],
        2:[(0.333,3,0.0,False),(0.333,0,0.0,False),(0.333,6,0.0,False)],
        3:[(0.333,4,0.0,False),(0.333,0,0.0,False),(0.333,6,0.0,False)]
    },
    4:{
        0:[(0.333,1,0.0,False),(0.333,3,0.0,False),(0.333,5,0.0,False)],
        1:[(0.333,7,0.0,False),(0.333,3,0.0,False),(0.333,5,0.0,False)],
        2:[(0.333,3,0.0,False),(0.333,1,0.0,False),(0.333,7,0.0,False)],
        3:[(0.333,5,0.0,False),(0.333,1,0.0,False),(0.333,7,0.0,False)]
    },
    5:{
        0:[(0.333,2,0.0,False),(0.333,4,0.0,False),(0.333,5,0.0,False)],
        1:[(0.333,8,1.0,True),(0.333,4,0.0,False),(0.333,5,0.0,False)],
        2:[(0.333,4,0.0,False),(0.333,1,0.0,False),(0.333,7,0.0,False)],
        3:[(0.333,5,0.0,False),(0.333,1,0.0,False),(0.333,7,0.0,False)]
    },
    6:{
        0:[(0.333,3,0.0,False),(0.333,6,0.0,False),(0.333,7,0.0,False)],
        1:[(0.666,6,0.0,False),(0.333,7,0.0,False)],
        2:[(0.666,6,0.0,False),(0.333,3,0.0,False)],
        3:[(0.333,7,0.0,False),(0.333,3,0.0,False),(0.333,6,0.0,False)]
    },
    7:{
        0:[(0.333,4,0.0,False),(0.333,6,0.0,False),(0.333,8,1.0,True)],
        1:[(0.333,7,0.0,False),(0.333,6,0.0,False),(0.333,8,1.0,True)],
        2:[(0.333,6,0.0,False),(0.333,4,0.0,False),(0.333,7,0.0,False)],
        3:[(0.333,8,1.0,True),(0.333,4,0.0,False),(0.333,7,0.0,False)]
    },
    8:{
        0:[(0.333,5,0.0,False),(0.333,7,0.0,False),(0.333,8,1.0,True)],
        1:[(0.666,8,1.0,True),(0.333,7,0.0,False)],
        2:[(0.333,7,0.0,False),(0.333,5,0.0,False),(0.333,8,1.0,True)],
        3:[(0.666,8,1.0,True),(0.333,5,0.0,False)]
    }
}
```

## OUTPUT:
![266676221-c784b237-419b-4e3f-b7b0-3d5affa10f32](https://github.com/KeerthikaNagarajan/mdp-representation/assets/93427089/b82ccb0a-06d8-41ec-8315-06e1e4bcb903)


## RESULT:
Thus a real world problem is represented as Markov Decision Problem in the following ways successfully:

1. Graphical Representation
2. Python Representation
