# NumGen
This program is utilized to create thousands of validated phone numbers in a matter of seconds. As of now NumGen only generates numbers with a +1 country code, and all states/provinces inside the country.

## How NumGen is Used:
NumGen uses parameters, which are passed as you launch the python file via terminal.

Example: python NumGen.py -a 1000

Example: python NumGen.py --benchmark

Example: python NumGen.py -amount 100

Example: python NumGen.py -b

### Parameters:
-a AMOUNT, --amount AMOUNT   -> Using this parameter sets the amount of numbers to generate. (Mandatory)

-b, --benchmark   -> Using this Paramter runs 5, 10 seconds benchmarks of NumGen to see how many numbers your system is capable of generating every 10 seconds.
