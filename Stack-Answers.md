```
def play(data):
    if data == None:
        return
    if data.is_leaf() == True:
        resp = input(data.data + '(t/f)? ')
        if resp.upper() == 'T':
            print('That is right!')
        else:
            print('Sorry study a little more.')

    else: 
        resp = input(data.data + '(t/f)? ')
        if resp.upper() == 'T':
            play(data.right)
        else:
            print('Sorry study a little more.')


data = T_Node('An animal can lay eggs and still be a mammal.', T_Node('The tallest land animal is not the biggest animal.'))
play(data)
```
