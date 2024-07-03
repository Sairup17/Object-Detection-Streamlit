# Object Detector App

This application uses the Faster R-CNN model to detect objects in uploaded images. The model is trained on the COCO dataset and can detect various objects such as people, cars, bikes, and more.

## Features

- Upload an image and detect objects using Faster R-CNN.
- View the detected objects with bounding boxes.
- Navigate between different sections: Home, About, and Information.
- Custom design with different fonts and colors.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Saurabhraj2002/object-detector-app.git
    cd object-detector-app
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Run the Streamlit app:
    ```sh
    streamlit run app.py
    ```

2. Open your web browser and go to `http://localhost:8501`.

3. Use the sidebar to navigate between the Home, About, and Information pages.

## File Structure

- `app.py`: The main Streamlit application code.
- `requirements.txt`: List of required Python packages.

## Screenshots

![Home Page](![image](https://github.com/Saurabhraj2002/Object-Detection-Streamlit/assets/137194324/68047501-1d7b-49bd-b9b3-3f7fbb406bfa)
)
![Predictions](![image](https://github.com/Saurabhraj2002/Object-Detection-Streamlit/assets/137194324/6d7b2500-5136-4743-9203-19253ac0e01a)
)

## Technologies Used

- Python
- Streamlit
- PyTorch
- torchvision
- PIL
- numpy
- matplotlib

## Custom CSS

Custom CSS is used to enhance the appearance of the app, including different fonts and colors.

## Contact

Created by [Saurabh Raj](https://www.linkedin.com/in/saurabh-raj-7b1894268/). Feel free to contact me!

## License

This project is licensed under the MIT License.



