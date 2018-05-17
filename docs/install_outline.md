Install mountainlab-js (https://github.com/flatironinstitute/mountainlab-js)
* Install prerequisites: nodejs, python3 with pip, mongodb
* Clone `mountainlab-js repo`, and `npm install`
* Add `mountainlab-js/bin` to your path
* Configure using `ml-config`
* Test using `ml-list-processors`
* Clone plugin packages (ml_ephys and ml_ms4alg) into `~/.mountainlab/packages/`
* Compile each plugin package using `pip3 install --upgrade -r requirements.txt`
* Test that the new processor packages are registered: `ml-list-processors`

Install ephys-viz (https://github.com/flatironinstitute/ephys-viz)
* Clone the repo, and `npm install`
