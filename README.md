# Refactoring Python: Why and how to restructure your code

From the PyCon 2016 talk in Portland, OR ([officlal schedule link](https://us.pycon.org/2016/schedule/presentation/2073/)).

[Slides are here](https://docs.google.com/presentation/d/1o9SWhgtGmk5NfddReoRzinu1kBbHLKmIWWZ0nnpuZ_o/edit?usp=sharing) and embedded below:

<iframe src="https://docs.google.com/presentation/d/1o9SWhgtGmk5NfddReoRzinu1kBbHLKmIWWZ0nnpuZ_o/embed?start=false&loop=false&delayms=10000" frameborder="0" width="480" height="389" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

## Example code

Here are full Jupyter notebooks for each of the examples in the slides:

- [Example 1: Extract variable](Extract Variable.ipynb)
- [Example 2: Extract Method](Extract Method.ipynb)
- [Example 3: Add Parameter, Introduce Parameter Object](Add Parameter, Introduce Parameter Object.ipynb)
- [Example 4: Extract Class, Move Field, Move Method](Extract Class, Move Field, Move Method.ipynb)

To run the demo code (must have Python3 installed):

1. Download this repo
2. Go into the repo directory on your local machine
2. `pyvenv .`
3. `source bin/activate`
4. `pip3 install -r requirements.txt`
5. `jupyter notebook`
6. Control-C to kill the notebook when you're done
7. `deactivate` to leave the Python environment

## License

The code within is [released under the Apache 2.0 License](LICENSE).
