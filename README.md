# lesson35
try:
     x = int( input( "son kiriting: " ) )
     y = int( input( "yana son kiriting: " ) )
     print( x, '/', y, '=', x/y )     
    x = int(input("son kiriting: "))
    y = int(input("yana son kiriting: "))
    print(x, "/", y, "=", x / y)
except ZeroDivisionError:
     print( "0 ga bo'lib bo'lmaydi" )
    print("0 ga bo'lib bo'lmaydi")
except ValueError:
     print( "Bu son emas" )
    print("Bu son emas")
except:
     print( "Xato yuz berdi!" )
    print("Xato yuz berdi!")
 20 changes: 10 additions & 10 deletions20  
35-exceptions/javoblar-35-02.py
@@ -1,22 +1,22 @@
print("x/y hisoblovchi dastur")
while True:
    x = input( "x ni kiriting: " )
    x = input("x ni kiriting: ")
    if x.isdigit():
        x=int(x) 
        x = int(x)
    else:
        print("Bu son emas!")
        continue
    
    y = input( "y ni kiriting: " )

    y = input("y ni kiriting: ")
    if y.isdigit():
        y=int(y) 
        y = int(y)
    else:
        print("Bu son emas!")
        continue
    
    if y==0:

    if y == 0:
        print("y 0 bo'lishi mumkin emas!")
        continue
    else:  
        print( x, '/', y, '=', x/y )
        break
    else:
        print(x, "/", y, "=", x / y)
        break
