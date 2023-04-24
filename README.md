# `kksubs` Sample Projects

This repo contains a sample "Hello World!" project to illustrate how to use `kksubs` to add subtitles, among other template projects you can experiment with to understand how the program works.

Ensure you are in the same directory as this readme. Create a virtual environmennt and install `kksubs` from Github.
```bash
virtualenv venv
.\venv\Scripts\activate
pip install git+https://github.com/pain-text-format/kksubs
```
Run `kksubs-compose` to apply subtitles.
```bash
kksubs-compose -p hello-world
```
Here `-p` is a project directory flag, it tells the program to add subtitles for the project located in the `hello-world` project directory.

You can find the subtitled images in the `helloworld/output/` directory. You can also make changes to the drafts or `styles.yml` file to experiment with other options. Expected result is shown in the `target` directory.