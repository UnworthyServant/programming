## pandas
* df[c].unique()
* df.iloc[:, :-1].values; iloc[:, -1]; [[]] get df back
* df.info(), df.describe()
* df.index
* df['date'].dt.date
* df['c'].astype('int')
* Custom conversion: df['c'].apply(f)
* np.where
* np.to_datetime(); np.to_numeric()

### Options
* pd.options.display.max_rows; pd.set_option('display.max_rows')

## Jupyter
### Tips
* complete: tab, shift tab, ?prefix
* show all output: from IPython.core.interactiveshell import InteractiveShell
InteractiveShell.ast_node_interactivity = "all"
* magics: %env; %lsmagic; %debug; %prun 1+2; !ls; !!ls; %%sh; %timeit
* from IPython.display import display, HTML
display(HTML(df.to_html()))
* startup file: ~/.ipython/profile_default/ipython_config.py
* %load_ext memory_profiler; %memit


### Nbextensions
* ExecuteTime: Display when each cell has been executed and how long it took.
* Table of contents.
* memory_profiler

## Reference
* [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/) 
* [IPython Cookbook](https://ipython-books.github.io/)
