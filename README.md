# Module-5-Challenge
HW 5 Matplotlib
I needed some help in the beginning when dropping the duplicate mouse ID. I had a couple TAs help. One helped me with using loc
duplicate_mouse_data = df.loc[df["Mouse ID"] == "g989"]
duplicate_mouse_data

and to get the correct data frame, you could just keep all the Mouise IDs except for the duplicate one. 
clean_df = df.loc[df["Mouse ID"] != "g989"]
