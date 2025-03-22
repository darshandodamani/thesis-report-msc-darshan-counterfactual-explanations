# A Counterfactual Explanation Approach Using Deep Generative Models

<!-- This is a latex template for the Software Engineering group at Bauhaus University Weimar. -->

<!-- This template is based on a Latex template from the vrsys group at Bauhaus University Weimar [available from GitHub]{https://github.com/vrsys/thesis-template}.

Mostly based on the [great template](https://git.webis.de/code-generic/code-webis-thesis) of the [webis group](https://webis.de/) at Bauhaus University Weimar. -->

<!--% \begin{enumerate}
%     \item \textbf{Validity:} Validity measures the ratio of the counterfactuals that actually have the desired class label to the total number of counterfactuals generated. Higher validity is preferable. Most papers report it. A counterfactual $x'$ is valid iff it actually changes the classification outcome with respect to the original one, i.e.,  $b(x') \neq b(x)$.
    
%     \item \textbf{Proximity (Minimality of Change):} The modifications to the input should be as small as possible while still achieving a prediction change $d(x,x') is minimized$ $d(x,x′)<δ$. Where $d(x,x')$ is a distance function (e.g., Euclidean distance, cosine similarity) and $δ$ is a predefined threshold. For example, A realistic counterfactual for a traffic sign should keep the shape and location unchanged while modifying brightness or contrast. Distance metrics like the L1 norm (MAE), L2 norm (MSE), and logcosh are common. Lower values of average distance are preferable.
    
%     \item \textbf{Plausibility:}  Counterfactual explanations should remain realistic within the observed data distribution.
%     For instance, if an autonomous vehicle classifies a sign incorrectly due to lighting conditions, a valid counterfactual should propose plausible changes, such as adjusting brightness. However, a counterfactual suggesting a triangular STOP sign would be unrealistic, as STOP signs are always octagonal.
    
%     \item \textbf{Actionability:} For counterfactuals to be useful in decision-making, they should suggest actionable changes.
%     In finance, for example, if a loan application is rejected, an actionable counterfactual might suggest increasing the applicant’s income or paying off existing debts. However, suggesting changing an immutable feature such as age or gender would be unrealistic and unethical.
% \end{enumerate}-->