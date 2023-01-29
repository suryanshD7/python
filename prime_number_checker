print('Welcome to prime number checker! ')

user_input = int(input('Enter the number to check: '))

def prime_number_checker(user_input):

    flag = True
    if user_input == 2:
        print(f'{user_input} is Prime number')
    elif user_input <=1:
        print('Enter a valid number! ')
    else:
        for i in range(2,user_input):
            if user_input % i == 0 :
                print(f'{user_input} is not a Prime number')
                flag = False
                break;
        if flag:
            print(f'{user_input} is Prime number! ')

prime_number_checker(user_input)
