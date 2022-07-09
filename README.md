# categorical_data_encoding
This function encodes the categorical data and returns the dataframe with encoded data. 

    Args:data: pandas dataframe
         column: column name. It needs to be a list and categorical column
         method: one_hot or label_encoding
    Returns: pandas dataframe with encoded categorical data.

    We encode the categorical data because many algorithms are not able to handle the categorical data.
