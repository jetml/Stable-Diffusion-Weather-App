# JetML AI Weather App

## Check it out at  https://weather.jetml.com

<a href="https://weather.jetml.com">
    <img src="images/Ashland,%20Oregon-2023-01-01.png" width="400">
    <img src="images/Ashland,%20Oregon-2023-01-02.png" width="400">
</a>

This was a project to demonstrate using Stable Diffusion 2 to generate weather forecasts for Oregon destinations using the JetML machine learning platform. Learn more at https://www.jetml.com/stable-diffusion-weather-app/. 

### Based on ###

https://huggingface.co/stabilityai/stable-diffusion-2

https://github.com/Stability-AI/stablediffusion

https://www.weatherapi.com/



## How to Run on JetML

1. Create a new JetML workflow using either the 16gb+gpu or 64gb+gpu instance types.
2. Sign up for a https://www.weatherapi.com/ account and add the api token as a JetML workflow enironment variable named WEATHER_API_KEY.
3. Run the workflow and clone this repo into your workspace using git clone

    git clone jetml/Stable-Diffusion-Weather-App

5. Open weather-stable-diffusion.ipynb and run the notebook

