# SAFEST - the Static And dynamic Fault trEe analySis Tool

SAFEST provides modelling and analysis of fault trees and supports both static fault trees (SFT) and dynamic fault trees (DFT).
The tool uses the Storm-dft library of the [Storm modelchecker](https://www.stormchecker.org/) in its backend.

## Dependencies
Make sure that [Docker](https://www.docker.com/) is installed on your computer and is currently running.

SAFEST is known to work with the following browsers:
- Google Chrome
- Firefox


## Running SAFEST:

Step 1: Clone the repository.

```
git clone https://github.com/DGBTechnologies/SAFEST.git
```


Step 2: Set the working directory and the license key.

For Linux/Mac OS Terminal:
```
export WORK_DIR=$PWD
export LICENSE_KEY="LICENSE_KEY_STRING"
```

Step 3: Run docker compose file

```
cd SAFEST
docker-compose pull
docker compose down
docker compose up
```

Step 4: Open link 

- http://127.0.0.1:8080
