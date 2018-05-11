# ecg-analysis-mit-bih
I test different approaches to analyzing electrocardiograms and test them on the MIT-BIH Arrhythmia Database.

I recommend that you use a virtual python environment, and run python 3. Open your terminal, navigate to this folder and run the following in the terminal:

    virtualenv --no-site-packages -p path/to/python  env/

If you do not already have the `virtualenv`python module, then run:

    pip3 install virtualenv

To activate your new virtual environment run the following in the terminal:

    source env/bin/activate

To install the requirements for the notebook run:

    pip3 install -r requirements.txt

Finally, to launch the notebook run:

    jupyter notebook