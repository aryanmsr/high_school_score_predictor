<h1 align="center">
  High School Score Predictor
</h1>
<p align="center">
  This notebook contains the code of a prototype ML-based score-predicting feature using past Portuguese student data.
</p>

<div align="center">
  <img alt="Demo" src="https://github.com/aryanmsr/aryanmsr.github.io/blob/main/content/featured/CaimConsulting/demo1.png" />
</div>

The dataset includes attributes such as past student grades, demographic, social, and school related factors. After performing some basic visualizations, data pre-processing and feature engineering, the data was modelled under binary/five-level classification and regression tasks. Some models' hyperparameters were fine-tunded to optimize performance, whereas other models with already competitive results did not undergo this procedure to prioritize computational time over performance. Towards the end of this notebook, to tackle class imbalance, the SMOTE (Synthetic Minority Oversampling Technique) was performed, yielding more competitive results.

I am still learning everyday and I am always open to new ideas that can help me improve my code, therefore, if you have any feedback, queries or concerns regarding this notebook, please feel free to email me at aryanmsr@gmail.com.

- Link to dataset: https://archive.ics.uci.edu/ml/datasets/Student+Performance
- Link to the original research paper from which this notebook is based on: http://www3.dsi.uminho.pt/pcortez/student.pdf 
- Link to code: https://github.com/aryanmsr/high_school_score_predictor/blob/master/final_notebook.ipynb

## Snapshots
### Some Visuals

<figure class="half">
  <table>
    <tr>
      <td>
        <img src="https://github.com/aryanmsr/high_school_score_predictor/blob/master/Screen%20Shot%202022-01-13%20at%203.49.39%20PM.png" alt="fig1" width = 500>
      </td>
      <td>
        <img src="https://github.com/aryanmsr/high_school_score_predictor/blob/master/Screen%20Shot%202022-01-13%20at%203.49.51%20PM.png" alt="fig2" width = 500>
      </td>
    </tr>
    <tr>
      <td>
        <img src="https://github.com/aryanmsr/high_school_score_predictor/blob/master/Screen%20Shot%202022-01-13%20at%203.50.00%20PM.png" alt="fig3" width = 500>
      </td>
      <td>
        <img src="https://github.com/aryanmsr/high_school_score_predictor/blob/master/Screen%20Shot%202022-01-13%20at%203.50.08%20PM.png" alt="fig4" width = 500>
      </td>
    </tr>
  </table>
  <figcaption>Plots visualizing the distribution of various features.</figcaption>
</figure>

### Model Accuracies 

<figure class="half">
  <div align="left">
    <img alt="fig5" src="https://github.com/aryanmsr/high_school_score_predictor/blob/master/Screen%20Shot%202022-01-13%20at%203.50.43%20PM.png" width=500 />
    
  </div>
  <figcaption>The Plot above shows the final accuracies of some of the models used in the project.</figcaption>
</figure>
