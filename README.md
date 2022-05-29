# Python-Assignment
f=10
m=65
 
print("Feet     Meters      Feet      Meters")
print("---------------------------------------")
def footToMeter():
   for f in range(1,11):
       m = f * .305
       print(f,"     ",m)
 
def meterToFoot():
   for m in range(20,66,5):
       f = m/0.305
       print("                  ",m,"      ",f)
      
footToMeter()
meterToFoot()
