# Monthly Production Statistics

This Python script processes monthly production data from machines and provides statistical insights. The program reads data from a file named `monthly_production.txt`, analyzes it, and prints machine-wise statistics, including monthly production totals, the number of production days, and the daily average production.

## Usage

1. Ensure you have a file named `monthly_production.txt` with the required data.
2. Run the script, and it will process the data and display the statistics.

## Code Overview

The script consists of three main functions:

### `takeProductionData(infile, productionTotals, dayCount)`

This function reads data from the input file and updates production totals and day counts for each machine.

### `statistics(productionTotals, dayCount, machineCount)`

This function calculates and prints machine-wise statistics, including monthly production totals, the number of production days, and the daily average production.

### `main()`

The main function orchestrates the entire process. It opens the input file, calls the necessary functions, and handles potential file-related errors.

## Sample Output

The script generates an output that looks like:

```plaintext
Machine No   Monthly Production  Number of Production Days   Daily Production
----------   ------------------  -------------------------   ----------------
1            123456789012345678  20                         6172839450617283934
2            987654321098765432  15                         65843621406543765432
...
Total        111111111111111111  35
Max Machine  2
Max Production  987654321098765432
