# honeyPurityPredict

Required Downloads
To run this project, you need to install the following libraries. You can install them by typing the commands below in your terminal:

bash
pip install streamlit
pip install pandas
pip install joblib
pip install pycaret[all]
Once the downloads are complete, navigate to the directory where the stream.py file is located using the terminal. For example:

bash
cd "folder_name"
Then, type the following command in the terminal:

bash
streamlit run stream.py
You can open the application in a web browser (Chrome, Mozilla, or Internet Explorer) by entering the following URL in the address bar:

arduino
http://localhost:8501
Changing the Models
You can change the model being used by modifying the line of code in stream.py that loads the model. For example, the following line:

python
model = load_model('AutoMLbest_model')
can be changed to use a different model located in the same directory. For instance, to use a model named OneLayerdNetwork, you would modify the code as follows:

python
model = load_model('OneLayerdNetwork')
By making these changes, you can switch to the desired model.

![streamlitPredict](https://github.com/apokaslan/honeyPurityPredict/assets/100843601/0d3d45bc-f1ab-4009-bd2a-d91ec8b1abf1)





