# OncoAi-Vision
Early cancer detection is vital for survival, but many cases are diagnosed late due to inadequate screening methods. Our project leverages AI to analyze medical imaging and EHRs, identifying high-risk patients for timely intervention.

### Problem Statement

Cancer remains one of the leading causes of death worldwide, with early detection being a critical factor in improving survival rates. Unfortunately, many cancers are diagnosed at advanced stages due to a variety of challenges associated with current screening methods. Traditional diagnostic tools often lack the sensitivity to detect subtle signs of cancer, which can result in missed opportunities for timely intervention.

Screening methods, such as mammograms, CT scans, and MRIs, can be effective, but they often depend on human interpretation, which is subject to variability and error. Moreover, existing systems may not integrate well with electronic health records (EHRs), limiting their ability to leverage comprehensive patient data for risk assessment. This fragmentation can lead to delays in diagnosis, worsening outcomes for patients.

Additionally, there is a significant gap in identifying high-risk individuals who would benefit from more intensive screening. Many patients may not be adequately monitored or referred for additional tests, further delaying critical treatment. 

To address these pressing issues, our project seeks to harness the power of artificial intelligence (AI) to analyze medical imaging alongside patient data from EHRs. By doing so, we aim to create a robust solution that enhances the accuracy of early cancer detection, identifies high-risk patients, and facilitates timely interventions. This approach not only has the potential to improve survival rates but also to transform the landscape of cancer care, making it more proactive and effective.


## Setup
1. Install dependencies: `pip install -r requirements.txt`
2. Prepare your datasets in the `data/` directory.
3. Run `train.py` to train the model.
4. Use `predict.py` to make predictions on new images.

## Future Work
- Incorporate genomic data analysis.
- Develop a user-friendly web interface for healthcare providers.
