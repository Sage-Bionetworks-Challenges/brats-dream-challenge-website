####! This is an unranked leaderboard of the participating users/teams during the **Validation Phase (August 2 - 22, 2021)**.

Each submission includes the number of cases that user/team has uploaded and the average metrics for those cases.

${synapsetable?query=SELECT id AS "Submission ID"%2C createdOn AS "Date"%2C submitterid AS "Participant/Team"%2C cases%5Fevaluated AS "Cases Evaluated"%2C Dice%5FET%2C Dice%5FTC%2C Dice%5FWT%2C Hausdorff95%5FET%2C Hausdorff95%5FTC%2C Hausdorff95%5FWT%2C Sensitivity%5FET%2C Sensitivity%5FTC%2C Sensitivity%5FWT%2C Specificity%5FET%2C Specificity%5FTC%2C Specificity%5FWT  FROM syn26003289 WHERE submitterid NOT IN %283416939%2C 3393723%29 AND status %3D %27ACCEPTED%27 AND submission%5Fstatus %3D %27SCORED%27 ORDER BY Date DESC&showquery=false}