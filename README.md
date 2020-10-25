# 6sense_model_predict

## Introduction
This notebook is for training the 6sense data through different models (such as Random Froest, KNN, XGBoost and so) on and find the best fit model to predict several variables including call disposition, best day of week to call and best hour to call.

### The Data:
#### data link: https://6sense.sharepoint.com/Shared%20Documents/Forms/AllItems.aspx?id=%2FShared%20Documents%2FData%20Science%2FData%2DX%2Fdata&p=true&originalPath=aHR0cHM6Ly82c2Vuc2Uuc2hhcmVwb2ludC5jb20vOmY6L2cvRXVJdlhTQ0lLUnRPa0hZdFQ5QWFkb0VCNDU0LTZOU2lhQ2pDQVpmcVluQWxVZz9ydGltZT1saFdwWWQ1NDJFZw
<ul>
<li>calls.csv: a timeline of outgoing sales calls and the disposition of those calls</li>
<li>events.csv: any activities that we have on record taking place before the phone calls were made</li>
<li>companies.csv: the industry and employee count of the companies</li>
<li>people.csv: the people who were called, along with their job level and function and the ID of the company they work for</li>
</ul>


