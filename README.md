# Hero Movement Speed Web App

This is a simple web application that allows users to upload a CSV file containing hero data and find the hero with the lowest movement speed along with its HP.

## Features
- Upload a CSV file with hero data
- Identify the hero with the lowest movement speed
- Display hero details, including an image, movement speed, and HP
- Styled UI with animations and a background image
- Includes a video preview

## Technologies Used
- HTML
- CSS (custom styles and animations)
- JavaScript (CSV file parsing and data processing)

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/hero-movement-speed.git
   ```
2. Navigate to the project directory:
   ```bash
   cd hero-movement-speed
   ```
3. Open `index.html` in your browser.

## Usage
1. Click the file upload button and select a CSV file containing hero data.
2. Ensure that the CSV file includes the following column headers:
   - `hero_name`
   - `movement_spd`
   - `hp`
3. Click the "Find Hero" button to identify the hero with the lowest movement speed.
4. The results will be displayed with the hero's name, movement speed, HP bar, and a corresponding image.

## CSV Format Example
```csv
hero_name,movement_spd,hp
HeroA,250,3000
HeroB,260,3200
HeroC,240,2800
```

## Notes
- Ensure that hero images are available in `.webp` format, named in lowercase and without special characters (e.g., `hero_name.webp`).
- The page uses a background image (`background.jpg`) and a video (`wanwan.mp4`). Make sure these files exist in the project directory.

## License
This project is licensed under the MIT License.

## Author
[rhythm](https://github.com/rhythm0914)

