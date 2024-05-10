# Project-1
- Used Xpert Learning Assistant (via UNC Bootcamp site) to clean up <distance = geodesic((offense_lat, offense_lon), (public_lat, public_lon)).miles> and <offense_df.loc[offense_index, f'Distance_to_Public_{public_index}'] = distance> code.

- Assistance from Justin Moore in setting up for loop and concat_df <for place in public_places:
    temp_df = offense_df.loc[offense_df[place] <= 1]
    filtered_data.append(temp_df)>, <concat_df = pd.concat(filtered_data, ignore_index=True).drop_duplicates("OBJECTID")>