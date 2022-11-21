# nfgbnn
 print("Idézőjelek közé írva.")
  print('Aposztrófok közé írva.') 
  # Ez egy egysoros komment.
  print('alma') # Így is írhatunk kommentet

  # Ez egy
  # többsoros komment
    
  ''' 
  Többsoros kommentet írhatunk
  3 aposztróf vagy 3 idézőjel közé írva.
  Így szoktuk megadni általában a program vagy programrészlet leírását.
  '''
  # print("alma")
   szam = 5
    szo = 'alma'
    szo2 = "alma"
    
    print(szam)
    print(szo)
  # Mivel az input függvény mindig sztringet ad vissza,
  # ha számot kérsz be, ne feledkezz meg a típusátalakításról!
  adat = input('Adj meg egy számot! ')
  szam = int(adat)

  # rövidebben:
  szam = int(input('Adj meg egy számot! '))
   x = 7
  y = 3

  # összeadás
  print(x + y)

  # kivonás
  print(x - y)

  # szorzás
  print(x * y)

  # osztás
  print(x / y)

  # maradékos osztás, az osztás maradékát adja eredményül
  print( x % y)
  szo1 = 'alma'
  szo2 = 'fa'
  print(szo1 + szo2)
  szoveg1 = 'Adj meg '
  szoveg2 = 'egy szamot!'
  print(szoveg1, szoveg2)

  x = 9
  y = 2
  print('9 % 2 = ', x % y)

  # Az input függvénnyel ez azonban nem lehetséges, hibát eredményez!
  input(szo1, szoveg2) # HIBÁS!!!
