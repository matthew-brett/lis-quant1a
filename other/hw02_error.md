Anthony kindly pointed out that I made a mistake in the last part of the
homework. The cells I give you for counting the number of white and not-white
people refer to the full data frame `eth_outcome`, rather than the data frame
without missing values `valid_eth_outcome`.  For example, I gave you this
cell:

```python
n_wb = np.count_nonzero(eth_outcome['recoded_eth'] == 'White British')
n_wb
```

But - to correspond with what you have up to that point, that cell, and the
ones below it, should refer to the `valid_eth_outcome` data frame - as in:

```python
n_wb = np.count_nonzero(valid_eth_outcome['recoded_eth'] == 'White British')
n_wb
```

It's up to you whether you want to fix that series of cells that I gave you,
to replace `eth_outcome` with `valid_eth_outcome`.   I will accept answers
using my original cells, that I gave you, or cells with the
`valid_eth_outcome` numbers instead.  Bear in mind your current tests look for
results based on the original numbers, so may find that you get test failures
if you do fix these cells.  Obviously I'll fix the tests when I mark the
notebook, but still, the safe option is for y'all to leave the cells as they
are, and proceed with the simulation.
