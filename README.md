# SAFEST - the Static And dynamic Fault trEe analySis Tool

SAFEST provides modelling and analysis of fault trees and supports both static fault trees (SFT) and dynamic fault trees (DFT).
The tool uses the Storm-dft library of the [Storm modelchecker](https://www.stormchecker.org/) in its backend.

## Dependencies
Make sure that [Docker](https://www.docker.com/) is installed on your computer and is currently running.
Docker is available for Windows, Linux and macOs.

SAFEST is known to work with the following browsers:
- Google Chrome
- Firefox

Follow the following steps to run SAFEST on [Linux and macOS](#running-safest-on-linux-and-macos) or on [Windows](#running-safest-on-windows).


## Running SAFEST on Linux and macOS

Step 1: Clone the repository.

```
git clone https://github.com/DGBTechnologies/SAFEST.git
```

Step 2: Make sure that Docker is running.

Step 2: Set the working directory and the license key.

Step 3: Open a terminal and navigate into the SAFEST directory
```
cd path/to/SAFEST
```

Step 4: Set the working directory and the license key.
```
export WORK_DIR=$PWD
export LICENSE_KEY="LICENSE_KEY_STRING"
```

Step 5: Download all necessary docker containers for SAFEST.
This step might take a while.
```
docker-compose pull
```

Step 6: Start SAFEST
```
docker compose down
docker compose up
```

Step 7: Open the link in a web-browser.
- http://127.0.0.1:8080

To rerun SAFEST in the future, simply execute Steps 6 and 7.


## Running SAFEST on Windows

Step 1: Download the [repository](https://github.com/volkm/SAFEST/archive/refs/heads/main.zip) and extract it to a folder.

Step 2: Make sure that Docker is running.

Step 3: Open the Windows command prompt and navigate into the SAFEST directory
```
cd path/to/SAFEST
```

Step 4: Set the working directory and the license key.
```
set WORK_DIR=%cd%
set LICENSE_KEY=LICENSE_KEY_STRING
```

Step 5: Download all necessary docker containers for SAFEST.
This step might take a while.
```
docker-compose pull
```

Step 6: Start SAFEST
```
docker compose down
docker compose up
```

Step 7: Open the link in a web-browser.
- http://127.0.0.1:8080

To rerun SAFEST in the future, simply execute Steps 6 and 7.
