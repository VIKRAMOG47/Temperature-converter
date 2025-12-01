print("welcome to temperature converter")
print("press '1' to convert from celsius to fahrenheit")
print("press '2' to convert from fahrenheit to celsius")
choice = input()
if choice == '1':
  print("please enter the temperature in celsius")
  celsius = float(input())
  fahrenheit = (celsius * 9/5) + 32
  print(f"{celsius}°C is {fahrenheit}°F")
elif choice == '2':
  fahrenheit = float(input("please enter the temperature in fahrenheit"))
  celsius = (fahrenheit - 32) * 5/9
  print(f"{fahrenheit}°F is {celsius}°C")
else:
  print("Invalid choice. Please enter '1' or '2'.")




  PS C:\Users\vidha> & C:/Users/vidha/AppData/Local/Microsoft/WindowsApps/python3.13.exe c:/Users/vidha/.vscode/temperature.py
welcome to temperature converter
press '1' to convert from celsius to fahrenheit
press '2' to convert from fahrenheit to celsius
1
please enter the temperature in celsius
60
60.0°C is 140.0°F
PS C:\Users\vidha> 
