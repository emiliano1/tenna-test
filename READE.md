# Optimized Math

This program will print messages for the positive integers from 1 to 100.

## Running the program

Use `ruby` to execute program:

```shell
$ ruby optimized_math.rb
```


> Example output:
```shell
The number '1' is odd.
The number '2' is even.
The number '3' is divisible by three.
The number '4' is even.
The number '5' is odd.
The number '6' is divisible by two and three.
The number '7' is odd.
The number '8' is even.
The number '9' is divisible by three.
The number '10' is even.
```

# Thread Synchronization

This program will print positive integers from 1 to 100 using two threads.

## Running the program

Use `ruby` to execute program:

```shell
$ ruby thread_synchronization.rb
```


> Example output:
```shell
Thread 1: The number is '1'
Thread 2: The number is '2'
Thread 1: The number is '3'
Thread 2: The number is '4'
Thread 1: The number is '5'
Thread 2: The number is '6'
Thread 1: The number is '7'
Thread 2: The number is '8'
Thread 1: The number is '9'
Thread 2: The number is '10'
```  

# Running the tests

First install the `rspec` gem

```shell
$ gem install rspec
```

Then run

```shell
$ rspec optimized_math_test.rb
$ rspec thread_synchronization_test.rb
```
