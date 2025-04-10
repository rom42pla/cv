# Run the webserver

## Install pre-requisites

- Install dependencies:

    ```bash
    sudo snap install hugo
    ```

- Create a new virtual environment and install Python dependencies:

    ```bash
    conda create --name cv -y
    conda activate cv
    conda install pip -y
    pip install -r requirements.txt
    ```

## Start the webserver

Simply run `serve.sh`:

```bash
bash serve.sh
```

# Publications management

## Add publications

To add publications, add their respective BibTex citations into a `.bib` file in the root.
In my homepage I've split publications into primary and secondary, so I have two files , [`publications.bib`](publications.bib) or [`publications_interdisciplinary.bib`](publications_interdisciplinary.bib).

