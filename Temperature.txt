class Temperature:
    def convertFarheniet(self):
        Fahrenheit = int(input(("Enter a temperature in Fahrenheit: ")))

        Celsius = (Fahrenheit - 32) * 5.0 / 9.0

        print('temperature is', Celsius )
    def convertCelcius(self):
        Celsius = int(input(("Enter a temperature in Celsius: ")))

        Fahrenheit = 9.0 / 5.0 * Celsius + 32

        print('TEMPERATURE IS', Fahrenheit,)

T1 = Temperature()
T1.convertFarheniet()
T1.convertCelcius()