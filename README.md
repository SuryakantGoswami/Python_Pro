# Python_Pro
class Test:
	def Emp(Self, first, Secound):
		Self.first = first
		Self.secound = Secound

class Test1(Test):
	def showData(Self):
		a = 100
		b = 200
		return a,b

obj_Test1 = Test1()
obj_Test1.Emp(1111,2222)
print(obj_Test1.showData())

# ne line