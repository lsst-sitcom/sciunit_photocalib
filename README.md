# README.md for sciunit_photo_calib

- author : Sylvie Dagoret-Campagne
- affiliation : IJCLab/IN2P3/CNRS
- creation date : 2024-10-27
- last update : 2024-10-27

## Sylvie Dagorest's branch to study LSSTComCam

## Note on embargo

- to prevent images inside the notebook, I have installed a pre-commit hook to clear the notebooks before commit.
I have  followed the instructions on this page https://zhauniarovich.com/post/2020/2020-06-clearing-jupyter-output/



I could run the following command by hand

     jupyter nbconvert --ClearOutputPreprocessor.enabled=True --inplace *.ipynb


But the pre-commit hook help me if I forget to run this command.
