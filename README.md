# Coming-Years-Most-Popular-Music-Prediction
As we are living in the era of technology, everything we enjoy changes quickly. The music industry is no different. With emerging music streaming services in the last few decades, we can easily find our favorite music, but its trend also is modifying its shape more quickly. Therefore, in this project, I wanted to design a predictive model by combining two different steps to predict the new characteristics of music since it was difficult to reflect the changing trend in a simple machine-learning model.

## Implementation
### Data
Spotify Music Dataset 
### First Step
- Preprocessed data to get the data of recent years
- Combined parallely simple regression models on each feature of the data
- Built Music Genre Prediction model by using XGBoost
### Second Step
- Cacluated cosine similarities between predicted music data and new music data
- Made the list of predicted N top most popular songs by sorting calculated similarities
- Predicted music genre that will be most popular in the coming year
### Future Improvements
- Analyze the effect of the popularity of artists
