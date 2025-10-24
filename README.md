This is to reproduce pyvista issue [8040](https://github.com/pyvista/pyvista/issues/8040).

To reproduce run 

```
uv sync --all-extras
```

to install all the dependencies.

Next open vscode (or cursor), open this project, open test.ipynb, select the .venv in the project when selecting the kernel and then run the first cell.
