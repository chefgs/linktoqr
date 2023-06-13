# Convert URL link to QR Code
## Purpose
Code in this repo will help to generate QR from the given URL.

## Install the executable
- Run the command below to install the executable
```
mkdir -p ~/go/bin && go install github.com/chefgs/linktoqr@latest
```

## How to run the executable
- The executable will be stored in `~/go/bin` path
- Go to `~/go/bin` path to execute the Go executable file or add the `~/go/bin` directory to PATH environment variable, so the executable can be accessed anywhere from terminal path or command prompt
- Run the below commands
```
cd ~/go/bin
./linktoqr
```

## Access to QR generator portal
- Once we execute the code, it will run the portal in `localhost` port `1718`
- So access the QR generator portal by accessing it from `http://localhost:1718`
- Enter the URL in the text box 
![enter url to convert](https://github.com/chefgs/linktoqr/assets/7605658/f58999e2-0b7b-462e-a3ea-36a5a8e60b4e)
- Click `Show QR` button
- Now, you can see the QR code for the entered URL.
![image](https://github.com/chefgs/linktoqr/assets/7605658/7f8e58d3-e3cd-4e48-a7af-2f4b87c68e67)

- You can save this image as `.png` file and use it where ever you want.
