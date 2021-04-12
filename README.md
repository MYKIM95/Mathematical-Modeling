# Mathematical-Modeling
Mathematical Modeling and Data Analysis Project about Chicken Pox

# Project Description
In history, there are lots of diseases which threaten human’s life, for example, Black death, SARS, MERS and
COVID-19. Numerous people are dead from those serious epidemics, however, people always find out how to overcome those diseases by medicine, vaccine and passive immunity. From this, we are curious about how passive immunity can affect the pandemic period. This report will make an MSIR model with mathematical modeling assumption
on the epidemic. The Varicella data set provided by Minnesota will be used to analyze how the passive immunity
affects our model. We will set the various situations for the MSIR model, and investigate how those changes affect the
result.

# Modeling Assumption
First, we need to set up modeling assumptions for our MSIR model. The real world data and data analysis might
have some difference because there are numerous unexpected outside effects in the real world. Hence, we need to
restrict our MSIR model on some conditions as below.
1. There should not be people who get other disease. It causes a population change.
2. Ignore change in population due to immigration and emigration. It causes a population change.
• Population change by other disease, immigration, or emigration can impact every group of MSIR models,
se we need to make our MSIR model with fixed population size.
3. Can never become susceptible again. We assume people get perfect immunity when recovered.
• All population should move in the progress of M → S → I → R. If not, the MSIR model does not make
sense.
4. Constant rate of infectivity
• We are making the MSIR model with the one disease, so that disease must not change or be stronger during
the MSIR model period.
5. The population is homogeneous.
6. No isolation, No vaccination.
7. Only people can spread disease (not animal).
• Those changes (age, gender, isolation, vaccination, or animal spread) can affect the result of the MSIR
model.
Also there is some weakness in our MSIR model. First, we assumed that the population is homogeneous, so there
will be some error when we apply real world data. Second, the MSIR model would not be suitable if the population
levels are small.

# MSIR Epidology Model Description
In the MSIR model, we are looking for the change or impact of four groups of population under given time. At the
start, we have four groups which are M, S, I and R. M is passively immune class, S is susceptible class, I is infectious
class and R is recovery class. All populations have to flow from M to R as like the figure below. Unlike original SIR
model, there will be births and deaths added to the compartments.
• The Passive immune compartment consists of those individuals who have never been infectious and have immunity of the disease. This will skip the infectious class and move on to recovery group. The passive immune
class population size at time t is denoted by M(t) with M(t) ≥ 0.
• The susceptible compartment consists of those individuals who have never been infectious but capable of getting
the disease and become infectious. This group would move into the infectious group if infected. The susceptible
population size at time t is denoted by S(t) with S(t) ≥ 0.
• The infectious compartment consists of those individuals who are infectious and capable of transmitting the
disease to the susceptible group. Infectious group will remain in this group for a given period and will be moved
onto recovery group. The infectious population size at time t is denoted by I(t) with I(t) ≥ 0.
• The recovery compartment consist of those individuals who had the disease and are dead, or have recovered
and are permanently immune from the disease. The is of recovery population at time t is denoted by R(t) with
R(t) ≥ 0.
• All parameters, α,µ, γ,β,Ω defined below can be assumed to be positive.
– Birth rate: α
– Death rate: µ
– Rate of non-passive immune people: Ω
– Rate of infectivity: β
– Recovery rate: γ
Further descriptions in pdf.

## Model Simulation and Conclustion
Read pdf file.
