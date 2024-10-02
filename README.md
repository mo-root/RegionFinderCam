# CamPaint 🎨 - by Moin

Our first assignement for CS10 at Dartmouth. 
A Webcam-based drawing application that allows users to paint in real-time using regions identified by color detection. 

``` There is clear Encapsulation and inheritance, as well as polymorphisim in the assignement.```

![Moin Mattar's Video - Oct 1, 2024](https://github.com/user-attachments/assets/7c965ecd-4aab-421f-a130-7b85bec1f35b)

## Features ✨

- **Region Detection** 
- **Dynamic Painting**
- **Color Selection**
- **Pause/Resume Functionality**
- **Brush Size Control**

## Installation Instructions 🛠️

1. **Download OpenCV**: 
   - Download the OpenCV zip archive: `opencv.zip`.
   - Extract the archive and import the SDKs into your IDE.

2. **Clone the Repository**:
   ```bash
   git clone https://your-repo-url.git
   cd src
   Run (perferable from an IDE) PaintCampBonus.java
   OR 
   Javac CamPaintBonus.java

# CamPaint Bonus 🎨
In ``` Campaint.java``` I have all the minimal features, and I added extra features in ```CamPaintBonus.java```

## CamPaint Bonus: Usage Instructions 💡


- **Mouse Click**: Select a color from the webcam image to add to your brush palette.
- **`w`**: Display the live webcam feed.
- **`r`**: Show the recolored image with detected regions.
- **`p`**: Display your painting (only active when painting is enabled).
- **`c`**: Clear the painting regardless of the current state.
- **`o`**: Save the recolored image as `recolored.png`.
- **`s`**: Save your painting as `painting.png`.
- **`t`**: Toggle the ability to change brush color on/off.
  
### Brush Color Options:
- **`b`**: Set the brush color to blue.
- **`g`**: Set the brush color to green.
- **`e`**: Set the brush color to red.

### Brush Size Controls:
- **`+`**: Increase the brush size.
- **`-`**: Decrease the brush size (minimum size is 1).
- **`=`**: Reset the brush size to the default (5).

### Pause/Restart Painting:
- Painting can be paused or restarted using a variable toggle in the code (functionality can be implemented as needed).

### Note:
- Ensure to select your desired colors before starting to paint for the best experience! 🌈

