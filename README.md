# MSBD6000M-RL\_Assignment\_2

## 1. `MSBD6000M_Assignment2.ipynb`

* **Description**: Jupyter notebook implementing PPO training for Super Tic-Tac-Toe in a **simplified** environment.
* **Features**:

  * Diagonal win condition is 4-in-a-row.
  * Fallback always selects a valid adjacent cell.
* **Contents**:

  * Custom TF-Agents environment setup
  * Actor-Critic network and PPO agent configuration
  * Reward shaping and legal action masking
  * Training loop, logging, and evaluation

---

## 2. `MSBD6000M_Assignment2_Full_Env.ipynb`

* **Description**: **Complete** environment implementation based on the official assignment specification.
* **Differences from simplified version**:

  * Diagonal win requires 5 consecutive pieces.
  * If a fallback move is invalid, the turn is forfeited.
* **Contents**:

  * Updated game logic with full rule constraints
  * Additional experiments and analysis
  * Comparison with results from the simplified setting

---

## 3. `MSBD6000M_Assignment2_Unit_Test.ipynb`

* **Description**: Unit test notebook verifying environment and network correctness.
* **Contents**:

  * Test coverage for environment behavior, state validity, and reward computation
  * Policy distribution and masking checks
---

## 4. `MSBD6000M_Assignment_2_report.pdf`

* **Description**: Formal project report summarizing all design choices, experiments, and findings.
* **Contents**:

  * Problem definition and modeling analysis
  * Detailed implementation using TF-Agents
  * Comparison between simplified and full environments
  * Evaluation metrics, gameplay examples, and conclusions

---

## How to Use

1. Open the notebooks using **Jupyter Lab** or **Google Colab**.
2. Follow installation instructions in the notebook headers to set up dependencies.
3. Run all cells in order to reproduce training and evaluation.
4. Use the unit test notebook to verify implementation integrity.
5. Refer to the PDF report for complete explanation and experimental insights.

