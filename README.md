from abc import abstractmethod

2

6

class AbstrakcyjnySzablon:

def metoda szablonowa (self):

self.procedural()

self.procedura2()

self.procedura3()

self.procedura4()

self.procedura5()

e

self.procedura6()

7

8

9

10

11

12

Ө

def procedural(self):

print("Wykonuje procedure nr 1")

13

14

15

@abstractmethod

16

def procedura2(self):

17

pass

I

18

19

def procedura3(self): pass

el e

20

21

22

def procedura4(self):

23

pass

24

25

@abstractmethod

def procedura5(self): pass

27

28

29

def

procedura6(self):

print("Wykonuje procedure nr 6")

30

31

32

33

class Model1(AbstrakcyjnySzablon);

def procedura2(self):

print("Procedura nr 2 wywołane przez Modell")

34

35

36

def print("Procedura nr 5 wywołana przez Modell")

proceduras(self):

37

38

39

class Model2(AbstrakcyjnySzablon):

def procedura2(self):


