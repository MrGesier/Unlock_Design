# Unlock_Design
Code allowing to forecast price &amp; manage unlock (selling pressure)

# Dynamic Tokenomics Simulation Tool

## Overview
This Streamlit app provides an interactive dashboard for simulating tokenomics, including vesting schedules, dynamic market depth, and stochastic price modeling. Users can explore token unlock schedules, ROI dynamics, and market overflow conditions, making it ideal for analyzing token distribution strategies and market sustainability.

---

## Features

### 1. Tokenomics Inputs
- Define maximum token supply, initial token price, and simulation start offset.
- Choose between constant and stochastic price models (Black-Scholes).

### 2. Bear Market Periods
- Specify custom bear market periods with adjustable sell pressure coefficients.
- Visualize the impact of bear markets on ROI and overflow.

### 3. Vesting Schedule Editor
- Editable schedules for categories like Pre-Seed, Treasury, and Marketing.
- Adjust unlock percentages, lock-up periods, and sell pressure triggers.

### 4. Dynamic Market Depth
- Simulates evolving market depth with optional liquidity provisioning.
- Highlights overflow conditions when unlock values exceed market depth.

### 5. Rewards Allocation
- Uses logistic curve for dynamic reward distribution.
- Integrates ROI-triggered sell pressure adjustments.

### 6. Interactive Visualization
- Token unlock schedules with dynamic market depth and overflow.
- ROI progression with highlighted bear market periods.
- Cumulative overflow calculations using a range slider.

---

## Installation

1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd <project_directory>
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the application:
   ```bash
   streamlit run app.py
   ```
5. Open the application in your web browser at `http://localhost:8501`.

---

## Usage
1. Adjust parameters using the sidebar, including tokenomics inputs, bear market periods, and vesting schedules.
2. Analyze the outputs:
   - Visualize token unlock schedules and market depth dynamics.
   - Monitor ROI projections and cumulative overflow.
3. Use the range slider to calculate overflow for specific timeframes.

---

## Dependencies

```plaintext
streamlit
numpy
pandas
matplotlib
```

---

## File Structure
- `app.py`: Main application script.
- `requirements.txt`: List of dependencies.
- `README.md`: Documentation.

---

## Contributing
Feel free to open issues or submit pull requests for new features or improvements.

---

## License
This project is licensed under the [MIT License](LICENSE).
