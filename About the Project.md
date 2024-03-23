## Overview
<p> The ability to identify cars through license plate detection is an essential technique, but its efficacy is dependent on several variables, including image quality, lighting, and vehicle location. With an emphasis on e-challan, in-car parking, and vehicle identification, this project intends to develop a software system for recognizing license plates. The method is twofold: first, it identifies the plate numbers; second, it segments the plate to extract characters and numbers. Applications such as traffic management, automated toll collection, and law enforcement depend on this technology. </p>

----------
# Dataset
**Training Dataset**
* Source: Kaggle dataset titled "ALPR Character Train" 
<br>
https://www.kaggle.com/datasets/foolishboi/alpr-character-train

<p> Contents: This dataset comprises images of license plate characters used for training the model. It encompasses a diverse range of alphanumeric characters, capturing variations in fonts, styles, and layouts commonly found on license plates </p> 

**Testing Dataset**
* Source: Kaggle dataset containing synthetic images of UK license plates 
<br>
https://www.kaggle.com/datasets/saadbinmunir/uk-licence-plate-synthetic-images

<p> Contents: The testing dataset includes synthetic images of UK license plates, serving as a representative sample for evaluating the model's performance. Synthetic datasets can provide additional challenges, such as variations in lighting, perspective, and background, contributing to a robust evaluation. </p>

-----------
# Model Process
## Data Pre-processing
<p> The preprocessing process in our project involves using the OpenCV library to load an image from a specified file path, and potentially image resizing to standardize dimensions. This is crucial for consistency and compatibility with machine learning models. These steps are essential for preparing input data for analysis and model training. </p>

## Analysis
<p> The process entails obtaining two datasets: one with pictures of number plates and the other with alphanumeric characters. The picture data is preprocessed and enhanced using TensorFlow's Keras library, which broadens its diversity and improves the model's capacity to identify various number plate image variations. The model is trained using convolutional neural networks (CNNs), which pick up patterns and characteristics from the input images and progressively increase the model's accuracy in identifying alphanumeric characters. After that, the model uses optical character recognition (OCR) to identify and extract text from the number plate photos. This all-inclusive approach demonstrates the integration of machine learning algorithms and data mining techniques for number plate recognition, allowing for the precise recognition of text from number plate images.
</p>

## Model Design
<p> Using a variety of datasets containing numeric digits and alphanumeric characters, a model is trained for number plate recognition. This ensures high accuracy by enabling the model to learn complex patterns and variations. After that, the model uses advanced computer vision techniques to locate and identify the licence plate in an image that shows a car and its licence plate. Afterwards, using Optical Character Recognition (OCR) methods, it extracts text in alphanumeric characters from the designated area. This all-inclusive system is a useful tool for e-challan, in-car parking, and vehicle identification since it can reliably recognise and extract text from licence plates in a variety of real-world scenarios.
</p>

## Testing
<p>A user-friendly Graphical User Interface (GUI) is used in the testing phase of the number plate recognition system to enable smooth interaction with the model. Users of all technical backgrounds can access the content with the ability to upload images. After that, the model extracts text and detects license plate information, displaying the predicted text in a new tab in the browser. Because of its user-friendly design, the system is well-suited for functions like vehicle identification, in-car parking, and e-challan. Incorporating a graphical user interface (GUI) with interactive outcomes demonstrates the model's usefulness in practical situations.
</p>

-------
# UI OUTPUT

<p> The user interface (UI) is designed for a seamless and informative interaction with the number plate recognition system. It uses a graphical interface developed using Tkinter in Python, which processes an image and incorporates predicted text into an HTML template, representing alphanumeric characters on the detected license plate.

Tkinter and HTML are combined to enhance the user experience by creating a visually appealing HTML template that showcases input images and predicted text. This dynamically generated file opens in a new tab within the web browser, facilitating seamless communication between the Python backend and the web browser frontend.

The HTML template, combining Tkinter and HTML, creates an interactive and responsive user interface for the number plate recognition system. It includes headers, image displays, and predicted text for clarity and readability. This approach makes the system accessible to users with varying technical expertise.
</p>

## GUI with Tkinter

<p>The number plate recognition system's Tkinter customization improves its visual appeal and functionality by adding styling elements like buttons, labels, and frames, resulting in a modern, clean, and intuitive interface. The UI components are improved with padding, font specifications, a dedicated frame, and a balanced "Select Image" button, enhancing readability and visual consistency. The GUI is designed to enhance usability beyond visuals, with a file dialog for image selection and a responsive design that accommodates users with varying technical backgrounds, making it accessible and user-friendly.

In summary, The Tkinter customization in the number plate recognition system aims to enhance the user experience by incorporating styling elements, padding adjustments, and thoughtful layout structuring, thereby providing efficient and intuitive image processing for license plate recognition.</p>

## HTML View in Browser
<p>The number plate recognition system uses HTML code to present and visualize its output. The Python backend generates an HTML template after successful image processing and character recognition, presenting the results in a structured format. Key components include a title, image display, and recognized text, arranged strategically for a clear and concise representation. The title introduces the recognition system's purpose, while the image display embeds a base64-encoded representation of the input image. The HTML template incorporates the predicted text, representing alphanumeric characters on the license plate, using HTML tags like < p > and < h2 > for optimal readability and styling. 

The HTML template is saved and opened in a new tab within a web browser, facilitating a seamless transition from the Python backend to the frontend display, showcasing recognized text and images in an interactive and accessible manner.</p>


