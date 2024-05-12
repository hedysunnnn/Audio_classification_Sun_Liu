# Audio_classification_Sun_Liu

In this project, we explore the application of sentiment analysis through the lens of speech audio data to classify human emotions. Understanding the emotional underpinnings of human communication enhances several domains, particularly human-computer interaction (HCI), marketing, and entertainment. This report details our methodology, the technologies employed, and the potential impacts of our findings on these key areas, aiming to foster advancements in how machines understand and interact with human emotions.

Our data is sourced from the publicly available dataset named RAVDESS (introduction on Kaggle: https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio， full dataset: https://zenodo.org/records/1188976, The Ryerson Audio-Visual Database of Emotional Speech and Song). It’s a comprehensive dataset containing speech, songs, and videos with emotional expressions such as calm, happy, sad, angry, fearful, surprise, disgust, etc. For the speech audio recognition model, we specifically used the “audio_speech_actors_01-24” pack, which includes 1440 speeches voiced by 24 actors. The relative emotion distribution is shown below:

We explored two models: CNN and LSTM. Overall, CNN performed better in this audio classification task.
