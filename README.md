# database

## pandas

- Check that two dataframes are equal
  ```
  from pandas.testing import assert_frame_equal
  
  assert_frame_equal(df1, df2)
  ```
  This function checks that the content is the same and raise exceptions to explain any differences.
