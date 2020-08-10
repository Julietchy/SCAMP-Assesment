# SCAMP-Assesment
def fibonacci_numbers(num):
    num_1 = 0
    num_2 = 1
    series = 0
    for i in range(num):
        print(series, end=' ');
        num_1 = num_2;
        num_2 = series;
        series = num_1 + num_2;
 
num = int(input('Enter how many numbers needed to form a Fibonacci series:'))
fibonacci_numbers(num)
