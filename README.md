Here are some of the challenges I faced
Fuuny enough I had difficulty Locating the Correct Data Sheets
The original Excel file contained multiple sheets and sections of raw data. Identifying which sheet corresponded to which figure (e.g., Resting MO₂, Power Output) required careful attention and cross-referencing with the paper.

Mismatch Between Variable Names and Figures
Column names in the dataset (e.g., “Resting”, “Maximum PO (W/kg)”) often did not exactly match what was used in the figures (e.g., “Resting metabolic rate”, “Power Output”), making it difficult to confirm you were analyzing the right variable.

Understanding and Applying Permutation-Based Statistics 
Because this was new to me, the study used non-standard analysis methods (e.g., lmp() from the lmPerm package), which are not as commonly used as traditional ANOVA. Learning how to implement permutation ANOVA and interpret its output added complexity.

Replicating Figures Without Exact Code
The original paper did not provide code or exact plotting instructions, especially for non-bar graph figures like the cycle frequency plot. Recreating the visual style (e.g., shape coding, line connections, asterisks) required close inspection and careful ggplot customization. I was able to try to get it as close as visually possible but I believe accuracy mattered more

Interpreting Post-Hoc Results and Matching Group Letters
Assigning significance letters (e.g., “a”, “b”) based on post-hoc permutation test results required additional logic and careful interpretation. Small variations in P-values across runs also made consistency a challenge without setting a random seed. Before this I had no idea what a Post-Hoc was
