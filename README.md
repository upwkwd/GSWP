# GSWP
notes for introductory pandas module in python.
+ pd.series
  - It gives an output of one index and column each.
  - functions in series method of pandas.
    > a = pd.Series( [.........], index = [.....]) 
    - values -> gives output of column in series.
    - index -> gives the value of index
    - isnull -> tells us about the value is NAN in form of boolean
      ```
      >>>pd.isnull()
      ```
    - notnull -> tells us about the value is not NAN.
      ```
      >>>pd.notnull()
      ```
    - name -> it integrates with series functionality
      ```
      >>>a.index.name = "..."             ## gives name to the index.
      >>>a.name = "..."                   ## gives name to whole series
+ pd.DataFrame
  - It will produce multiple columns and indexes.
    - loc & iloc -> to navigate rows through index
    - del -> for deleting specific columns
      ```
      >>>del b["..."]
      ```
    - columns -> it gives output of columns in a dataframe
      ```
      >>>b.columns
      Index([.....], dtype=.........)
      ```
    - T -> Transpose the dataframe
      ```
      >>>b.T
      ```
    - values -> values contained in a DataFrame
      ```
      >>>b.values
      ```
### **Functionality**
  ## Reindexing
  It will apply to indexes to series and dataframe;
  ```
   c =  b.reindex([...])
  ```
  
    
    
