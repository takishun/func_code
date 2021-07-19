def data_time_cut(df,year_s,month_s,day_s,column,year_e,month_e,day_e):
    """
    時系列でデータを分割する関数
    """
    df2=df[pd.to_datetime(df[column]) >= datetime.datetime(year_s,month_s,day_s)]
    df3=df2[pd.to_datetime(df2[column]) <= datetime.datetime(year_e,month_e,day_e)]
    
    return df3
