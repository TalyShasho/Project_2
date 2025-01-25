CLEANING DATA FORMULAS

filter_to_new_excel
            Function to combine the data of multiple CSV and Excel files to a single Excel file with selected columns

        Parameters:
        folder_path: to the folder with the files for each subject.
        selected_columns: list of desired columns 
        final_data_path

calculate_average_rt
        Calculates the average RT for each music type for each participant and saves it to the new Excel file.

    Parameters:
    - trial_combined_path (str): The path to the input Excel file.
    - final_data_directory (str): The path to the directory where the output Excel file will be saved.

process_ppg_and_trial_data_to_excel
    Process PPG and trial data to calculate IS scores and to calculate PPG maen and save a consolidated Excel file.

    Parameters:
        ppg_folder (str): Path to the folder containing PPG files.
        trial_folder (str): Path to the folder containing trial files.
        output_file (str): Path to save the consolidated Excel file.



ANALISIS DATA FORMULAS

analyze_music_type_vs_IS
         Analyze the relationship between 'music_type' and 'IS'. returns a wiskers plot for each type of music.

    Parameters:
        df (pd.DataFrame): The input DataFrame containing 'music_type' and 'IS' columns.



plot_average_rt
    Plots the average reaction times (RT) for each music type.

    Parameters:
    - data (DataFrame): A pandas DataFrame containing columns 'participant_id', 'music_type', and 'RT'.



plot_pulse_rate_by_interoception
     Analyzes and plots changes in pulse rate grouped by interoceptive sensitivity (IS).

    Parameters:
        file_path (str): Path to the Excel file.
        sheet_name (str): Name of the sheet containing the data.

calculate_spearman_correlation
    calculate spearman correlation between valence rating and average PPG.

plot_valence_vs_interoception
    Plots the relationship between average valence rating and interoceptive sensitivity (IS).

    Parameters:
        file_path (str): Path to the Excel file.
        sheet_name (str): Name of the sheet containing the data.
