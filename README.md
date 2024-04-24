<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <img width="898" alt="BananaByte_Equitable_Pay_Image" src="https://github.com/Gatheroxign34/BananaByte-Total-Staff-Compensation/assets/94628744/8126fe1c-e480-42ed-acc7-e304165483e8">
</head>
<body>
    <h1> What factors influence total compensation, salary and yearly bonuses at BananaByte? </h1>
        <p> This python project explores a ficticious company BananaByte's entry level, mid-level, management level, and executive level staff members' total compensation, salary and yearly bonuses. </p>
    <b> <p> Inquiry:</b> Have you ever wondered if factors such as seniority, years of experience or gender influence total compensation? How about all three? </p> 
    <b> <p> Tools & Methods:</b> Python Pandas, Scipy Stats, Seaborn and ScikitLearn in a Python Notebook</p>
    <b> <p> Analysis:</b> In the exploratory data analysis phase it is clear that there's a correlation between gender and total compensation at the executive level with men garnering more pay overall than women by about 25%.
                 <li> At the executive level and management levels there's no correlation between seniority and total compensation. However, as you move above $400,000 in the management level specifically, there seems to be a correlation between senior and total compensation because there's no performance variable for executive leadership. </li>
                <li> I've made an interactive PowerBI dashboard to help our ficticious BananaByte HR team see the connections between Years of Experience, Years of Seniority, Performance, Yearly Bonuses, and Total Compensation. K-means_4, K-means_5, K-means_6, and K_means_7 clusters illuminate correlations between years of experience and salary, years of experience and yearly bonuses, total compensation and performance, as well as yearly bonus and performance respectively</li>
                <li> The dashboard allows HR leadership staff to filter between job level and job family to see whether entry level, manager level, senior level, mid-senior level, and executive level staff's salaries and total compensation are connected to their performance, years of experience or seniority.</li> 
                <li> The dashboard shows characteristics for each cluster. Leadership staff is denoted by the color orange. We know this because K-means_6 and K-means_7 clusters involve performance, orange has "0" as it's cluster for performance, helping HR to understand that for executive leadership bonuses are connected to seniority rather than years of experience or performance.
                <li> If HR staff filter job level to entry level, K-means_6 and K-means_7 clusters show that bonuses and total compensation (salary + bonus) are only connected to performance since years of experience is not relevant to entry level staff.</li>
                <li> If HR staff filter job level to senior and mid-senior level, years of experience and performance affect salary level with one exception, and that is a staff member in product and project management where years of experience do not affect salary. </li>
&emsp;
<img width="500" alt="PowerBiEntrylevelImage" src="https://github.com/Gatheroxign34/BananaByte-Total-Staff-Compensation/assets/94628744/637b15a2-23f8-46dd-8067-057e612252ab">
&emsp;
<img width="500" alt="PowerBiLeadershiplevelImage" src="https://github.com/Gatheroxign34/BananaByte-Total-Staff-Compensation/assets/94628744/f0d33b07-20a0-4e2e-9ed0-397c27ebb608">
&emsp;
<img width="500" alt="PowerBiDataEngineeringFemaleStaffImage" src="https://github.com/Gatheroxign34/BananaByte-Total-Staff-Compensation/assets/94628744/87564a12-8480-46ad-89b4-ae91a059c9cd">
&emsp;
<img width="500" alt="PowerBiDataEngineeringMaleStaffImage" src="https://github.com/Gatheroxign34/BananaByte-Total-Staff-Compensation/assets/94628744/ea211794-7c89-4b5f-aea6-7498d0b1c644">
&emsp;
       <b> <p> Recommendations:</b> If BananaByte were a real company we would want to examine issues with equality for total compensation based on gender at the executive level. We might want to investigate seniority as it relates to female executives total compensation. And, at the Senior level investigating data science and engineers salaries for male vs. female staff members. 217,337.00 is the highest male salary in data science and engineering while 202,274.10 is the highest female salary in data science and engineering. To transform this dynamic HR can look at the level of experience versus level of performance for female data scientists and engineers to make more equitable decisions for salary levels.  

<a href = "https://colab.research.google.com/drive/1Cf268X3bLugLUfCPIaP9y8EYZN2O3T2z?usp=sharing"> Interactive Python Notebook </a>  
</body>
</html>
