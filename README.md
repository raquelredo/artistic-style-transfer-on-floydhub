# Artistic style transfer using Floydhub

Running deep learning projects can be a tedious job - installing the dependencies, downloading datasets, getting a gpu, etc.

To make things simpler, [Floydhub](https://www.floydhub.com) sets everything up for you.

In this project we'll be running a jupyter notebook on floydhub servers to do style transfer.

## Setup floydhub

Create an account on [Floydhub](https://www.floydhub.com). You get 100 hrs free GPU usage on signup.

Install the floyd-cli on your machine using `pip install -U floyd-cli`

Log in using the command line by running `floyd login`

Paste the authentication token from the site

*Now you are ready to go*

## Starting the project

Clone this repo and cd into it

Then run `floyd run --mode jupyter --gpu --env tensorflow-1.0 --data jq4ZXUCSVer4t65rWeyieG`

This will run a jupyter notebook on a gpu with tensorflow and some other basic libraries and mount the vgg19 dataset in the `/input` directory. Checkout the [floydhub documentation](http://docs.floydhub.com/home/using_datasets/) for more details

Open the jupyter notebook using the link and experiment with it.

---

*Khatam*
