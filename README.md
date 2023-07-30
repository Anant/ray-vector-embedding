# ray-vector-embedding
This is a quick demo for how you can use Ray to ingest text into Astra for Vector Search



## Setup

### Clone the Repo
To get started, you need to get the code onto your machine. So Start by cloning this GitHub repository. If you have git installed, you can do this by running the following command in your terminal:

```bash
git clone git@github.com:Anant/ray-vector-embedding.git
```

This will create a copy of the repository on your local machine.
Once you have cloned the repository, navigate into the directory:

```bash
cd ray-vector-embedding
```
### Install Prerequisites

To install the required packages for this plugin, run the following command:

```bash
pip install -r requirements.txt
```

### Setup A DataBase

In order to run the examples from this repo, you will need to set up a database and create a keyspace.
The details of how to do this should be found under the following link
<link>

### Setup the DataBase Details

Once you've got the database up and running and the keyspace created, make sure you download the bundle as described in the link above and get the keys needed to access your database.
Now open the local_creds_secrets.py file and make sure you fill in the details
```
client_id="<your-client_id>"
client_secret="<your-client_secret>"
db_keyspace="<your-keyspace>"
secure_bundle_path="<path-to-bundle>/secure-connect-<YOUR_DB_NAME>.zip"
```

## Launch a Google Colab

Upload this notebook, the local_creds_secrets, requirements.txt and your secure bundle, and start running the cells one by one.


#### To be fixed 

[//]: # ()
[//]: # (### Install Jupyter lab)

[//]: # ()
[//]: # (One important tool we will use here for an interactive coding is jupyter lab, or jupyter notebooks as well.  )

[//]: # (Jupyter lab in particular has more advanced functionalities than traditional notebooks. So if you don't have jupyter locally feel free to install the labs feature using the following command.)

[//]: # ()
[//]: # (```)

[//]: # (pip install jupterlab)

[//]: # (```)

[//]: # ()
[//]: # (### Run the notebooks)

[//]: # ()
[//]: # (After installing the jupyterlab, go to the terminal, inside your working directory &#40;or the directory you cloned as per the instructions above&#41; and run the following command:)

[//]: # ()
[//]: # (```)

[//]: # (jupyterlab)

[//]: # (```)

[//]: # (This should redirect you to the browser automatically, if not you should be able to see the instructions on how to navigate to the jupyter env on the terminal itself. )

[//]: # ()
[//]: # ()
[//]: # (Now you can start running the steps from the notebook &#40;executing the cells in order&#41;, to run the code that populates and extracts data from your AstraDB tables.)

[//]: # (The description of this can be found in the following link <link to the blog>.)

[//]: # ()
[//]: # ()
[//]: # (**Note**)

[//]: # ()
[//]: # (For this example the version of python used is: 3.10.11 )

[//]: # ()
[//]: # (As for the data, you will find a sample data under the data folder in this repository but feel free to use any dataset with the same schema. )

[//]: # ()
[//]: # ()
[//]: # (#### Resources)

[//]: # (For detailed information and code examples, refer to the following resources:)

[//]: # ()
[//]: # (AstraDB Documentation: https://docs.datastax.com/en/astra/docs/)
