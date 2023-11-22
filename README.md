# Entropy Calculation Methods

This Python script provides different methods for calculating entropy based on a given set of labels. Entropy is a measure of uncertainty or disorder in a dataset. The script includes four implementations of entropy calculation and demonstrates their usage with a sample set of labels.

## Project Structure

1. **`entropy_calculations.py`:**
   - The main script containing four different methods for entropy calculation.

2. **`README.md`:**
   - The README file providing an overview of the project and instructions on how to use the entropy calculation methods.

## Getting Started

Follow these steps to set up and run the entropy calculation script:

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/entropy-calculations.git
   cd entropy-calculations
   ```

2. Run the entropy calculation script:
   ```bash
   python entropy_calculations.py
   ```

   The script will output the entropy values calculated using different methods for the given set of labels.

## Entropy Calculation Methods

The script provides four different methods for entropy calculation:
1. `entropy1`: Using `scipy.stats.entropy` method with unique labels and counts.
2. `entropy2`: Custom implementation considering unique labels, counts, and probabilities.
3. `entropy3`: Utilizing `pandas` for value counts and normalized probabilities.
4. `entropy4`: Custom implementation considering unique labels, counts, and normalized probabilities.

## Sample Labels

The sample set of labels used for demonstration is:
```python
labels = [1, 3, 5, 2, 3, 5, 3, 2, 1, 3, 4, 5]
```

## Contributing

Contributions are welcome! If you have suggestions, find issues, or want to enhance the entropy calculation methods, please feel free to open issues or submit pull requests.

