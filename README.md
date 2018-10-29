# learn2com
Original Paper: [Learning to Communicate: Channel Auto-encoders, Domain Specific Regularizers, and Attention](https://arxiv.org/pdf/1608.06409.pdf)

## Installation
* Clone the repo and cd into it.

``` bash
git clone https://github.com/bitsandscraps/learn2com.git
cd learn2com
```
* Install the virtual evironment. I use `pipenv` but you may use whatever program you want.

``` bash
pipenv --three
```
If you want to use `pipenv`, you need to edit the [Pipfile](Pipfile).

## Run the Program

``` bash
pipenv run python -m learn2com.main
```
`learn2com.main` can take a handful of command-line options.
Check it out using the `-h` option, or reading through the [code](learn2com/main.py).

## TODO
* The delay channel is not working properly. The network fails miserably with delay regularization.
* The performance is not even close to what the paper is saying.
* Plot-generation code
* Localization networks


