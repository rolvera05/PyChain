# PyChain

Welcome to the repository of the Robust Blockchain Web Interface - a comprehensive solution offering a user-friendly web interface for a blockchain-based ledger system. Our system serves partner financial institutions by allowing secure monetary transfers between entities while ensuring the impeccable integrity of the data within the ledger.

_Last Updated: 2023-07-15_

---

## *Technologies*

- **Programming Language:** Python
- **Libraries:** Streamlit, DataClasses, Typing, Datetime, Pandas, Hashlib

---

## *Installation Guide*

If you don't have Python or Anaconda installed on your operating system:

-**[Install Python](https://www.python.org/downloads/)**
-**[Install Anaconda](https://docs.anaconda.com/free/anaconda/install/index.html)**

Follow the steps below to setup the development environment:

**1. Conda 'dev' Environment** - To run the main application you need to activate the 'dev' environment in your Anaconda installation. Use the following command to activate it:

        conda activate dev
If you don't have a 'dev' environment or unsure about it, create a new one with the following command and then activate it as shown above:

        conda create -n dev python=3.7 anaconda

**2. Libraries Installation** - Ensure that the required libraries, as mentioned in the Technologies section above, are installed in your environment. You can install them manually or use the `requirements.txt` file (if present) to install all dependencies at once.

**3. Clone Repository** - Once you have the development environment ready, clone this repository to your local machine. Navigate to the directory where you want to clone the repository and use the following command:

        git clone 'repository link here'

After cloning, navigate into the repository folder using the following command:

        cd 'repository name here'

---

## *Usage*

To use the Robust Blockchain Web Interface, ensure that you have Python and all the required libraries installed. Then follow the steps below:

1. **Navigate to the repository folder**: Change your current directory to the cloned repository's directory:

    ```bash
    cd <repository-name>
    ```

2. **Run the application**: Use the Streamlit library to run the application with the following command:

    ```bash
    streamlit run pychain.py
    ```

3. **Use the application**: Follow the on-screen instructions to utilize the functionalities of the ledger system.

Make sure you are in the correct directory and that the file "pychain.py" is present.

---

## *References*
- [Streamlit Usage](https://docs.streamlit.io/library/)
- [Pandas Usage](https://pandas.pydata.org/pandas-docs/stable/reference/index.html)
- [Python Data Classes](https://docs.python.org/3/library/dataclasses.html)

---

## *Summary*

The Robust Blockchain Web Interface is a versatile tool that enables partner financial institutions to perform secure monetary transfers. It maintains the absolute integrity of data within the blockchain-based ledger. Powered by Python and a collection of powerful libraries, the system offers a highly intuitive interface for easy operation. Users can simply run the "pychain.py" file using Streamlit to start utilizing the functionalities of the ledger system.
