
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Z7wxEWmcgMRur_TnA5Z5EYY4Rd9Ia_gb?usp=sharing)

# Face-Recognition

Missing Person Database &amp; Face Recognition
This repository contains a Python notebook **Face-Recognition.ipynb** implementing a face recognition system. This system allows users to add missing persons to a database along with their current and childhood photos and relevant information. Additionally, it provides functionality to search for a person's match based on an uploaded photo.

**The idea, in short,** is that any missing person, child, or lost elderly person suffering from Alzheimer's disease or anything else... can easily be identified by photographing them and matching these photos with the photos entered by the missing person's family in the database, and each photo contains complete information about him and contact numbers.

**Application**

The family of the missing person uploads a photo of him and information about him to the application
The application practices and learns the images so that it can compare them
""

Anyone who finds a lost person or child or suspects that he or she has been kidnapped should:

Open the application

Photographing a lost person, someone suspected of being kidnapped, or an elderly person who does not know who he is

After taking a picture of him, the application compares this picture with the pictures in the database or the closest picture to it and shows all the information recorded in it.

## Features

-   **Add Missing Persons:** Easily add missing persons to the database by providing their name, current photo, childhood photo, age, and contact information.
-   **Search Functionality:** Utilize face recognition to search for missing persons by uploading a photo. The system identifies potential matches based on facial features.
-   **Database Management:** Save and load the missing person database to/from a JSON file for persistent storage.


## Setup

To run the notebook, you need to have the following dependencies installed:

-   `face_recognition`
-   `cv2`
-   `numpy`
-   `json`

You can install the required packages via pip:
`!pip install face_recognition`

**To run the notebook, follow these steps:**

1.  Install the required libraries by running `!pip install face_recognition` in your Colab environment.
2.  Upload the provided Colab notebook to your Google Colab environment.
3.  Execute the cells in the notebook sequentially to utilize the functionalities provided.

## Usage

### Adding Missing Persons

1.  Execute the cell containing the `MissingPersonDatabase` class definition and related functions.
2.  Run the `add_multiple_missing_persons()` function to add one or more missing persons to the database. Follow the prompts to enter the necessary details.
3.  Provide the name, current photo, childhood photo, age, and contact information for each missing person.

### Searching for Missing Persons

1.  Execute the cell containing the `MissingPersonDatabase` class definition and related functions if not already executed.
2.  Upload a photo of the person you want to search for using the `handle_upload()` function.
3.  The system will perform a facial recognition search within the database and provide potential matches along with their associated information and similarity scores.

## Contributions

Contributions to improve and extend the functionality of this notebook are welcome. If you have any suggestions, bug reports, or feature requests, please feel free to open an issue or submit a pull request.

## Alternative Use Cases

**1. Criminal Investigation**

In criminal investigation, the system can be used to manage a database of known criminals or suspects. Investigators can upload photos of suspects, along with relevant information such as criminal history, aliases, and known associates. The search functionality can then be employed to match suspects' faces captured in surveillance footage or crime scene images with the database entries, aiding in identifying potential perpetrators or persons of interest.

**2. Event Management and Security**

Event organizers can employ facial recognition technology to manage attendee access and enhance event security. The system maintains a database of registered attendees and flagged individuals, such as banned attendees or VIP guests. Upon entry, attendees' faces are scanned and compared with the database entries to grant or deny access accordingly. This helps prevent unauthorized entry, identify potential security threats, and ensure a safe and secure event environment.

**3. Healthcare and Patient Management**

Healthcare facilities can utilize facial recognition for patient management and security purposes. The system maintains a database of patient profiles containing medical records, treatment history, and personal information. Healthcare professionals can use facial recognition to quickly identify patients during medical consultations or emergencies, access relevant medical information, and ensure accurate patient care delivery while maintaining patient privacy and security.

# Credits

This tool uses the `face_recognition` package 

This code I made using **ChatGPT 3.5**
