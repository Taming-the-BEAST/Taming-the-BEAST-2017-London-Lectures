# Taming the BEAST in London todo list


## Tutorials that need to be made from scratch
- Structured coalescent approximations in BEAST2
- Transmission tree inference in BEAST2 with SCOTTI
- Stochastic simulations in BEAST2 with MASTER

### How to create a new tutorial
- Create the tutorial in either LaTeX or Markdown. 
- Follow the instructions on the website: https://taming-the-beast.github.io/contribute/Contributing-a-new-tutorial/
- Tutorials should work in BEAST 2.4.6

---

## Tutorials that need to be improved
- Population structure using the multitype birth-death model
	- Check that it still works with the new version of BDMM
	- Change substitution model to HKY+Gamma and estimate shape parameter
	- Add better intuition on priors
	- Add explanation for setting matrices and interpreting the results with more than 2 demes
- Skyline plots (low priority)
	- Check and update bdskytools R package
	- Improve the text

---

## Tutorials that need to be checked 

In order of checking:
- Introduction to BEAST 2
- Prior selection and clock calibration
- ~~Substitution model selection:~~ Checked in BEAST 2.4.7 pre-release
- FBD tutorial
- Bacter tutorial
- Troubleshooting
- Skyline plots


### How to check a tutorial
- Install BEAST 2.4.7 pre-release
- Run through the tutorial and check that everything runs as expected
- If there are any mistakes please correct them!
- Make notes of figures that need to be updated because of changes in Beauti (please take a screenshot of the figure if possible).
- Correct any spelling errors, or rewrite parts that are vague or difficult to understand
- Add anything that you think is necessary for the tutorial


---

## Tutorials that have no markdown version (not essential)
- FBD tutorial
- Starbeast2 tutorials

### How to create markdown tutorial from LaTeX
- Install a local copy of the website: https://taming-the-beast.github.io/contribute/Building-a-local-copy-of-the-site/
- Get (buggy and incomplete) script from Louis to convert tex to md
- Hack what wasn't converted properly using the style guide: https://taming-the-beast.github.io/contribute/Style/

---

## Website todo list

On the website's git repo (blotter)