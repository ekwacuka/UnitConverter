# UnitConverter

Design a Unit Converter Computer Program:

1) Temperature from Fahrenheit to Celsius and back,
2) Convert Kilometer to Miles and back,
3) Convert Inches to Centimeters and back,

Your program should be menu driven with Options to pick from the running program.

### Unit Conversion Program 

print("\033[1m Options:  \033[0m")

def options_list():  ## define a function called print_menu and leave it empty
    
    print("[P] Print Options")   ## print a menu of options
    print("[C] Convert from Celsius")
    print("[F] Convert from Fahrenheit")
    print("[M] Convert from Miles")
    print("[KM] Convert from Kilometers")
    print("[IN] Convert from Inches")
    print("[CM] Convert from Centimeters")
    print("[Q] Quit" )


