![Screenshot 2024-07-31 003727](https://github.com/user-attachments/assets/eb1adb78-96d1-4194-8be8-bac197e0544f)

# Ventoy Goku Theme

This repository provides a custom Goku theme for Ventoy. Follow the instructions below to install the theme to your Ventoy drive.

## Prerequisites

- A USB drive or hard drive with Ventoy installed.
- Download the custom theme from this repository.

## Installation Instructions

1. **Clone the Repository**

    First, clone this repository to your local machine:

    ```sh
    git clone https://github.com/Amir-Hossein-Azimi/ventoy-goku-theme.git
    ```

2. **Extract the Theme**

    Navigate to the cloned repository and extract the theme files:

    ```sh
    cd ventoy-goku-theme
    unzip theme.zip -d extracted-theme
    ```

3. **Rename the Extracted Folder**

    Rename the extracted folder to `ventoy`:

    ```sh
    mv extracted-theme ventoy
    ```

4. **Copy to Ventoy Drive**

    Copy the renamed `ventoy` folder to the root directory of your Ventoy drive:

    ```sh
    cp -r ventoy /path/to/your/ventoy/drive/
    ```

    Replace `/path/to/your/ventoy/drive/` with the actual path to your Ventoy drive.

5. **Verify Installation**

    Safely eject your Ventoy drive and reinsert it. Boot from the drive to ensure the theme has been applied correctly.

## Troubleshooting

- If the theme does not appear, make sure the `ventoy` folder is correctly placed in the root directory of your Ventoy drive.
- Ensure that the Ventoy configuration file, if any, correctly references the theme files.

## Contributing

If you encounter any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

