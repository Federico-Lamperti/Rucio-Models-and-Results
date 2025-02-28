# Rucio Models and Simulation Results

This repository contains the complete simulation results and model files used in my Computer Science and Engineering Master Degree thesis at **Politecnico di Milano**. 
The provided models are implemented in **JMT (Java Modelling Tools)** and allow for flexible modifications to explore different scenarios. 
The results support the analysis conducted in the study and ensure reproducibility.

## Repository Contents

### JMT Models
Each model file corresponds to a different aspect of the system under study. Users can modify parameters within these models to explore different configurations and scenarios.

- **Model-Exponential**: JMT basic model with an **exponential arrival rate**.
- **Model-MMPP2**: JMT basic model with an **MMPP2 (Markov Modulated Poisson Process) arrival rate**.
- **Model-Arrival_Rate**: JMT model performing a **what-if analysis** on the arrival rate.
- **Model-RSE_Server_Sizing**: JMT model performing a **what-if analysis** on the **number of servers** in the RSE queue.
- **Model-RSE_Service_Times**: JMT model performing a **what-if analysis** on the **service times** in the RSE queue.
- **Model-IP_Relevance**: JMT model excluding the **IP queue** to evaluate its impact.

### Simulation Results
- **Simulation Results.xlsx**: Contains the results of the sensitivity analysis models, summarizing the key findings.

## Reproducibility and Customization
The provided models are **fully customizable**, allowing users to modify parameters such as arrival rates, service times, and queue sizes. This flexibility supports:
- **Reproducibility of results**
- **Exploration of alternative configurations**
- **Sensitivity analysis based on specific system needs**

## How to Use the Models
1. **Download JMT (Java Modelling Tools)** if not already installed.
2. **Clone this repository**:
   git clone https://github.com/Federico-Lamperti/Rucio-Models-and-Results.git
3. **Open the JMT model files** using the JMT tool.
4. **Modify parameters as needed** to explore different system behaviors.
5. **Run simulations** and analyze the results.

## License
This repository is distributed under the MIT License.
