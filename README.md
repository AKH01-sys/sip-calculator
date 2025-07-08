SIP Calculator & Planner
Overview
This is a comprehensive, interactive web application designed to help users plan and forecast their Systematic Investment Plan (SIP) investments. The tool is built with two primary modes: a Calculator to project the future value of investments, and a Planner to determine the necessary steps to reach a financial goal.

The application is built entirely with HTML, styled with Tailwind CSS, and uses Chart.js for data visualization. It provides a clean, user-friendly, and responsive interface suitable for all devices.

Features
General
Dual Modes: Switch between a forward-looking Calculator and a goal-oriented Planner.

Live Currency Conversion: Automatically converts the final corpus from INR to USD based on live exchange rates.

Responsive Design: Fully functional and aesthetically pleasing on desktop, tablet, and mobile devices.

Interactive UI: Smooth sliders and input fields provide a seamless user experience.

Calculator Mode
Future Value Projection: Calculate the estimated maturity value of your SIP investments.

Annual Step-up: Factor in an annual percentage increase in your monthly investment to see how it accelerates wealth creation.

Detailed Breakdown: View a year-by-year breakdown of your monthly investment amount when using the step-up feature.

Visual Growth Chart: An interactive line chart from Chart.js visualizes the growth of your investment versus the principal amount over time.

Clear Results: See a clear summary of your total invested amount, estimated returns, and the final projected value.

Plan Mode
Goal-Oriented Planning: Start with your financial target and work backward to create a plan.

Flexible Inputs:

Calculate the required investment period if you know how much you can invest monthly.

Calculate the required monthly SIP if you know your investment time horizon.

Optional Step-up: Toggle the annual step-up feature to see how it can help you reach your goals faster or with a smaller initial investment.

Instant Results: Get immediate feedback on your plan as you adjust the inputs.

How to Use
Calculator Tab
Monthly Investment: Enter the amount you plan to invest each month.

Annual Step-up (%): (Optional) Set a percentage by which your monthly investment will increase each year.

Expected Return Rate (%): Enter the annual rate of return you expect from your investments. The default is 12%.

Time Period (Years): Set the number of years you plan to stay invested.

Review Results: The right-hand panel will instantly update with the projected value (in INR and USD), a breakdown of invested amount vs. returns, and a growth chart.

Plan Tab
Set Your Goal: Enter your target amount in the "How much money do you need?" field.

Choose Your Mode:

Select "I know my monthly investment" to find out how long you need to invest. Enter your monthly SIP amount.

Select "I know my investment period" to find out how much you need to invest per month. Enter the number of years you can wait.

(Optional) Add Step-up: Check the "Include Annual Step-up?" box and enter a percentage to see its effect on your plan.

View the Plan: The results panel will show you either the required monthly SIP or the required time period to achieve your goal.

Technologies Used
HTML5: For the basic structure of the application.

Tailwind CSS: For all styling and layout, providing a modern and responsive design.

JavaScript (ES6): For all the calculation logic, DOM manipulation, and interactivity.

Chart.js: For rendering the interactive and visually appealing investment growth chart.

Frankfurter API: For fetching live currency exchange rates for the INR to USD conversion.
