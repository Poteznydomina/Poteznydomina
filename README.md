class FasadaPrzygotujSniadanie: def int(self, operacja_ekspres,

operacja toster):

self.operacja ekspres = operacja_ekspres self.operacja toster operacja_toster

def rob_sniadanie (self):

print("Ladovanie podsystemow")

self.operacja ekspresowa.wlacz_ekspres()

self.operacja_toster.wlacz_toster()

print("Zaczynam dziale")

self.operacja ekspres.rob_kawe () self.operacja toster.rob_tosty()

15

26

class OperacjaEkspres:

def wlacz ekspres (self):

17

18

print("Ekspres włączony. In Ekspres gotowy do działania")

19

20

def rob_kawe (self):

print("Kawa gotowa")

21

22

23

24

25

26

27

28

29

30

31

32

33

34

class OperacjaToster:

def wlacz toster (self):

print("Toster Właczony. In Toster gotowy do działania")

def rob tosty(self):

print("Tasty gotowe")

name main

ekspres = OperacjaEkspres()

toster = OperacjaToster()

fasada = FasadaPrzygotujSniadanie (ekspres, toster)

fasada.rob_sniadanie()


