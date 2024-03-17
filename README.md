# Plant Disease Classifier

Welcome to the Plant Disease Classifier repository! This repository contains the complete source code for the Plant Disease Classifier project, encompassing various stages from model training to deployment. The project is divided into multiple components, including model training using TensorFlow, API development with FastAPI, frontend website development using ReactJS, and API deployment using Docker containers on Google Cloud Run.

## Project Overview

The Plant Disease Classifier is a comprehensive project aimed at identifying plant diseases swiftly and accurately. It integrates machine learning techniques with modern web development to provide users with an intuitive platform for diagnosing plant health issues.

## Team Members

- **Alok Sharma** - Project Head
  - GitHub   - [Alok Sharma's Github Profile](https://github.com/Alok-2002)
  - LinkedIn - [Alok Sharma's Linkedin Profile](https://www.linkedin.com/in/alok-sharma2002-/)
  - Email    - [Sharmaalok02gwl@gmail.com](mailto:sharmaalok02gwl@gmail.com)

- **Sanskriti Yadav** - Project Co-Head
  - GitHub   - [Sanskriti Yadav's Github Profile](https://github.com/sanskriti-yadav)
  - LinkedIn - [Sanskriti Yadav's Linkedin Profile](https://www.linkedin.com/in/alok-sharma2002-/)
  - Email    - [Sanskriti2377@gmail.com](mailto:sanskriti2377@gmail.com)

## Key Components

### 1. TensorFlow Model Training

- **Training Dataset Acquisition**
Acquire insights into the dataset used for training our TensorFlow model. Explore the process of downloading and preprocessing the dataset sourced from Kaggle, ensuring its suitability for robust model training.

- **Model Development**
Dive deep into the development phase, where Jupyter Notebook files and Python scripts are meticulously crafted. Gain an understanding of the model architecture, hyperparameter tuning, and evaluation metrics employed to achieve optimal performance in classifying plant diseases.

### 2. FastAPI Backend Service

- **API Development**
Delve into the intricacies of building a resilient backend API using FastAPI. Explore the endpoints designed for model inference, authentication mechanisms, and error handling strategies implemented to ensure seamless interaction with the frontend interface.

- **Model Integration**
Discover how our backend service seamlessly integrates with the trained TensorFlow model to provide accurate predictions. Learn about the model loading process, input data validation, and response formatting to deliver reliable disease classification results to users.

### 3. ReactJS Frontend Interface

- **User Interface Design**
Uncover the design principles guiding the development of our user-friendly ReactJS frontend interface. Explore the intuitive layout, interactive features, and responsive design elements aimed at enhancing the user experience during image upload and result visualization.

- **Backend Communication**
Understand the underlying mechanisms enabling communication between the frontend interface and the backend API. Learn about data transmission protocols, error handling strategies, and asynchronous request handling techniques employed to ensure smooth data flow and real-time updates.

### 4. Docker Container Deployment

- **Containerization**
Explore the process of containerizing our backend API using Docker, facilitating seamless deployment and portability. Gain insights into Dockerfile configuration, image building, and container orchestration strategies to ensure consistent performance across diverse environments.

- **Cloud Deployment**
Witness the deployment of our Docker containers on Google Cloud Run, leveraging the scalability and reliability of cloud infrastructure. Learn about configuration settings, resource allocation, and monitoring tools utilized to optimize performance and ensure efficient processing of image data for disease classification.

## Website Images
Check out some screenshots of our web interface:


![Screenshot 2024-03-16 205033](https://github.com/Alok-2002/Plant_Disease_Classifier_Frontend/assets/93814546/9cc77c2e-eca5-4bca-a7c0-a530be47e1a2)


![Screenshot 2024-03-16 205119](https://github.com/Alok-2002/Plant_Disease_Classifier_Frontend/assets/93814546/c23603cd-984c-4dfc-93f1-c1f184b3ba2b)


## Getting Started

1. **Model Training**: Utilize the provided Jupyter Notebook files and Python scripts to train the machine learning model using TensorFlow.
2. **Dataset For Training** : Download the dataset folder provided in the repository.
3. **Backend API**: Set up the FastAPI backend service by following the instructions provided in the backend directory.
4. **Frontend Interface**: Set up the ReactJS frontend interface by following the instructions provided in the frontend directory.
5. **Docker Deployment**: Dockerize the backend API and deploy it using Google Cloud Run for scalable processing.

## How to Use the Website

1. Visit the deployed web interface [Plant Disease Classifier](https://plant-disease.netlify.app/).
2. Upload an image of a plant using the provided interface.
3. Wait for the classification results to be displayed.
4. Explore the disease classification and gain insights into the health of the uploaded plant.

## How to Use the Source Code

1. **Clone the Repository**: Start by cloning this repository to your local machine using the following command:

    ```bash
    git clone https://github.com/Alok-2002/Plant_Disease_Classifier_Full_Source_Code.git
    ```

2. **Setup Instructions**:
   - **Model Training**: Navigate to the `model_training` directory and follow the setup instructions provided there to configure and run the model training component.
   - **Backend Service**: Move to the `backend` directory and follow the setup instructions to configure and run the backend service.
   - **Frontend Interface**: Explore the `frontend` directory and follow the setup instructions to configure and run the frontend interface.

3. **Customization**:
   - Feel free to modify the code to suit your project requirements. Whether it's tweaking model parameters, adding new features, or refining the user interface, the source code is open for customization.
   
4. **Testing**:
   - Before deploying any modifications to production, ensure thorough testing locally to validate the changes. Test various scenarios and functionalities to verify the stability and functionality of your modifications.


## Project Structure

The repository is organized as follows:

```
plant-disease-classifier/
│
├── backend/             # Backend API development with FastAPI
│   ├── app/             # FastAPI application files
│   └── Dockerfile       # Dockerfile for containerizing the backend
│
├── frontend/            # Frontend website development with ReactJS
│   ├── public/          # Public assets and index.html
│   └── src/             # Source code directory
│
├── model_training/      # Model training with TensorFlow
│   ├── data/            # Dataset and preprocessing scripts
|   ├── models/          # Contains pretrained models.
│   └── notebooks/       # Jupyter Notebook files for model training
│
├── .gitignore           # Specifies intentionally untracked files to ignore
├── LICENSE              # MIT License file
└── README.md            # Project README file
```

## Dependencies

The project relies on various dependencies, including TensorFlow for model training, FastAPI for backend development, ReactJS for frontend development, Docker for containerization, and Google Cloud Run for deployment.

## Contributions

Contributions to this project are welcome. Whether you have suggestions for improving the model, enhancing the backend API, optimizing the frontend interface, or streamlining the deployment process, your contributions are valuable. Feel free to open an issue or submit a pull request—we appreciate your input!

## License

This project is licensed under the [MIT License](LICENSE), allowing you to use and modify the code in accordance with the terms of the license.

## Contact

If you have any questions or feedback, please don't hesitate to contact us [Sharmaalok02gwl@gmail.com](mailto:sharmaalok02gwl@gmail.com).
