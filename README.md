# Liquidity-Budgeting-Model

In this repo we are creating a liquidity budgeting model for a real estate company that would allow them to manage their working capital.
## Case Prompt:

You are in consulting business. You are hired by a small real estate company to help them manage their liquidity budgeting (or in other words to figure out the best timing of their expenses to minimize the extra cash needed). They want you to build for them a liquidity budgeting tool (an Excel model) that they will use to analyze and manage their working capital. 

The tool must contain enough flexibility to enable the future users to play with the model and conduct different analyses. Among others, the company requests a user-friendly and sophisticated input part where a manager can change not only the amount of money for a particular expense, but also the timing of this expense, e.g. in which month to fix something, they also want to have sensitivity analysis, scenario tool and automatic breakeven analysis, so it can be easily repeated for different scenarios. Overall, the model must be able to help analyzing the liquidity, see how much extra money is required, what happens if something goes not as planned, whether it makes sense to delay some costs etc.
Your contract includes building the model and performing the detailed liquidity analysis for the next year.

## Requirments:

The main goal is to calculate how much the company owners must insert money into the company so that the liquidity always stays positive. The tool must include liquidity budgeting for one year (12 months) starting from January and running until December.
1. Conduct Break-Even Analysis
2. Conduct Scenario Analysis 

---
<h2> Case Specifics: </h2>

<table>
  <thead>
    <tr>
      <th>Apartment</th>
      <th>Rent</th>
      <th>Water Payment In</th>
      <th>Condominium</th>
      <th>Loan Repayment</th>
      <th>Water Payment Out</th>
      <th>Maintenance</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Apartment 1</td>
      <td>345</td>
      <td>20</td>
      <td>-122</td>
      <td>-43</td>
      <td>-20</td>
      <td>-700</td>
    </tr>
    <tr>
      <td>Apartment 2</td>
      <td>440</td>
      <td>0</td>
      <td>-202</td>
      <td>0</td>
      <td>-40</td>
      <td>0</td>
    </tr>
    <tr>
      <td>Apartment 3</td>
      <td>600</td>
      <td>51</td>
      <td>-121</td>
      <td>-44</td>
      <td>-51</td>
      <td>-4000</td>
    </tr>
  </tbody>
</table>

<table>
  <tr>
    <th>Company Costs</th>
    <th>Amount</th>
  </tr>
  <tr>
    <td>Banking Costs</td>
    <td>-10</td>
  </tr>
  <tr>
    <td>MISC Costs</td>
    <td>-55</td>
  </tr>
  <tr>
    <td>Book Keeping Costs</td>
    <td>-300</td>
  </tr>
  <tr>
    <td>Taxes</td>
    <td>-440</td>
  </tr>
  <tr>
    <td>Quarterly MISC Costs</td>
    <td>-100</td>
  </tr>
  <tr>
    <td>Insurance Cost</td>
    <td>-200</td>
  </tr>
  <tr>
    <td>Belated Rent Receivable</td>
    <td>270</td>
  </tr>
  <tr>
    <td>Starting Liquidity</td>
    <td>2300</td>
  </tr>
</table>
