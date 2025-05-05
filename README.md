# # End-to-End-Chest-Cancer-Classification-using-MLflow-DVC #


## MLflow

- [Documentation](https://mlflow.org/docs/latest/index.html)

- [MLflow tutorial](https://youtube.com/playlist?list=PLkz_y24mlSJZrqiZ4_cLUiP0CBN5wFmTb&si=zEp_C8zLHt1DzWKK)

##### cmd
- mlflow ui


## For Dagshub
import dagshub
dagshub.init(repo_owner='shulazshan', repo_name='chest_cancer_prediction', mlflow=True)

import mlflow
with mlflow.start_run():

  https://dagshub.com/shulazshan/chest_cancer_prediction.mlflow


```bash
  export DAGSHUB_USERNAME=your-username
  export DAGSHUB_TOKEN=your-token
```