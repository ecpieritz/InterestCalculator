<h1 align = "center"> :fast_forward: Interest Calculator :rewind: </h1>

## 🖥 Preview
<p align = "center">
  <img src = "https://raw.githubusercontent.com/ecpieritz/InterestCalculator/master/public/img/interest-calculator-print.jpg" width = "800">
</p>

---

## 📖 About
<p>Create, using React, an application that should be able to calculate the appreciation/depreciation of a capital based on a monthly interest rate and time (months), using the compound interest concept.</p>

---

## 🛠 Technologies used
- CSS
- HTML
- Javascript
- React
- Hooks
- Materialize
- Node.js

---

## 📌Requirements
- Define the elements that will be considered as application state:
  - capital
  - monthly interest rate
  - period
- These elements will also be inputs of the application.
- Inputs shall be type number
  - Capital value goes from  0 to 100.000, step of 100
  - Interest rate value goes from -12 to 12, step of 0.1
  - Period value goes from 1 to 36, step of 1
- Output will be N boxes, being N the number of months, each one containing:
  - total value (amount after appreciation/depreciation of N months)
  - interest (value of appreciation/depreciation)
  - percentage (of appreciation/depreciation over the capital)
- The interest rate may be positive (appreciation) or negative (depreciation).
- Research and choose on of the compound interest formulas to implement.
- Improve interface using Materialize.
- Implementation shall use functional components and hooks.

---

## 🔍Development Tips
Use useEffect hook, with the three inputs as deps, to "watch" their change and recalculate the outputs.

---

## 🚀 How to execute the project
#### Clone the repository
git clone https://github.com/EPieritz/InterestCalculator.git

#### Enter directory
`cd InterestCalculator`

#### Download dependencies
`npm install`

#### Run the server
`npm start`

#### That done, open your browser and go to `https://localhost:3000/`

---
Developed with 💙 by Emilyn C. Pieritz
