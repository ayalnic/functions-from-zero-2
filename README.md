[![Codespaces Prebuilds](https://github.com/ayalnic/functions-from-zero-2/actions/workflows/codespaces/create_codespaces_prebuilds/badge.svg)](https://github.com/ayalnic/functions-from-zero-2/actions/workflows/codespaces/create_codespaces_prebuilds)

# functions-from-zero-2

## Step 1:  Configure Development environment

* Configure GitHub Codespaces or the equivalent (Cloud9, etc)
* Create scaffold for structure of project:  `Makefile` `requirements.txt`
* Optional (setup virtualenv) (install ipython outside of requirements.txt)

## Step 2:  Get interactive debugging working

* Use IPython and ipdb
* ipdb lets you run the code and use the command line tool when you set ipdb
```python
x = 1
y = 2
#import ipdb; ipdb.set_trace()
print(x + y)
```

## Step3:  Build a library and use it