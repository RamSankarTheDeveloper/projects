+---+----+-----+------+------+-------------------------+--------------+
| * | ** | **D | **Al | **L  | **What I did in the     | **What the   |
| * | Na | ata | gori | ibra | project**               | m            |
| T | me | set | thms | ries |                         | odel/program |
| y | ** | use | used | us   |                         | does**       |
| p |    | d** | and  | ed** |                         |              |
| e |    |     | sco  |      |                         |              |
| * |    |     | re** |      |                         |              |
| * |    |     |      |      |                         |              |
+===+====+=====+======+======+=========================+==============+
| N | [  | N   | Pu   | sp   | -   Program to          | -   Takes in |
| L | Qu | LP, | rely | aCy, |     preprocess entered  |     a        |
| P | es | d   | NLP  | N    |     text                |     textbook |
| ( | ti | ata | as   | LTK, |                         |     and      |
| c | on | set | of   | neur | -   Program to          |              |
| u | g  | c   | yet, | alco |     determine entities  |    generates |
| r | en | rea | is   | ref, |     using neural coref, |              |
| r | er | ted | ad   | pan  |     NER, repeated POS   |    questions |
| e | at | by  | ding | das, |     patterns etc        |     that of  |
| n | or | s   | deep | Nu   |                         |     5        |
| t | b  | elf | lear | mPy, | -   Program to blank    |              |
| p | as |     | ning | keyb |     out extracted       |    difficult |
| r | ed |     | and  | ert, |     entities to         | y/complexity |
| o | on |     | pr   | par  |     generate            |     levels   |
| j | B  |     | etra | rot, |     fill-in-the-blank   |              |
| e | lo |     | ined | r    |     questions (level 1  |    according |
| c | om |     | lang | egex |     question on Bloom's |     to       |
| t | 's |     | uage | as   |     taxonomy)           |     Bloom's  |
| ) | t  |     | mod  | of   |                         |     taxonomy |
|   | ax |     | els. | yet  | -   Program to          |              |
|   | on |     |      |      |     preprocess          | -            |
|   | om |     |      |      |     sentences that have |    Currently |
|   | y] |     |      |      |     keywords and        |     (NLP     |
|   | (h |     |      |      |     generate questions  |     only     |
|   | tt |     |      |      |     associating the     |     version) |
|   | ps |     |      |      |     entities and        |     the      |
|   | :/ |     |      |      |     keyword (level 3    |     model    |
|   | /g |     |      |      |     questions)          |     can      |
|   | it |     |      |      |                         |     generate |
|   | hu |     |      |      | -   Program to train    |     level 1  |
|   | b. |     |      |      |     pretrained language |              |
|   | co |     |      |      |     models to generate  |    questions |
|   | m/ |     |      |      |     further complex     |     and      |
|   | Ra |     |      |      |     questions           |              |
|   | mS |     |      |      |                         |    partially |
|   | an |     |      |      |                         |     level 3  |
|   | ka |     |      |      |                         |              |
|   | rT |     |      |      |                         |   questions. |
|   | he |     |      |      |                         |              |
|   | De |     |      |      |                         |              |
|   | ve |     |      |      |                         |              |
|   | lo |     |      |      |                         |              |
|   | pe |     |      |      |                         |              |
|   | r/ |     |      |      |                         |              |
|   | Qu |     |      |      |                         |              |
|   | es |     |      |      |                         |              |
|   | ti |     |      |      |                         |              |
|   | on |     |      |      |                         |              |
|   | -g |     |      |      |                         |              |
|   | en |     |      |      |                         |              |
|   | er |     |      |      |                         |              |
|   | at |     |      |      |                         |              |
|   | io |     |      |      |                         |              |
|   | n- |     |      |      |                         |              |
|   | al |     |      |      |                         |              |
|   | go |     |      |      |                         |              |
|   | ri |     |      |      |                         |              |
|   | th |     |      |      |                         |              |
|   | m- |     |      |      |                         |              |
|   | ba |     |      |      |                         |              |
|   | se |     |      |      |                         |              |
|   | d- |     |      |      |                         |              |
|   | on |     |      |      |                         |              |
|   | -b |     |      |      |                         |              |
|   | lo |     |      |      |                         |              |
|   | om |     |      |      |                         |              |
|   | s- |     |      |      |                         |              |
|   | ta |     |      |      |                         |              |
|   | xo |     |      |      |                         |              |
|   | no |     |      |      |                         |              |
|   | my |     |      |      |                         |              |
|   | /t |     |      |      |                         |              |
|   | re |     |      |      |                         |              |
|   | e/ |     |      |      |                         |              |
|   | ma |     |      |      |                         |              |
|   | in |     |      |      |                         |              |
|   | )( |     |      |      |                         |              |
|   | on |     |      |      |                         |              |
|   | go |     |      |      |                         |              |
|   | in |     |      |      |                         |              |
|   | g) |     |      |      |                         |              |
+---+----+-----+------+------+-------------------------+--------------+
| D | D  | st  | CNN2 | skle | reads and preprocess    | -   Given    |
| L | og | ock |      | arn, | image folders into      |     the      |
|   | -c | ima | (    | t    | train and test          |     image of |
|   | at | ges | WA=0 | qdm, | variables               |     a cat or |
|   | cl |     | .79) | ran  |                         |     a dog,   |
|   | as |     |      | dom, | create a CNN blackbox   |     the      |
|   | si |     |      | cv2, | model                   |     model    |
|   | fi |     |      | os,  |                         |     predicts |
|   | ca |     |      | ten  | callbacks               |     whether  |
|   | ti |     |      | sorf |                         |     if it    |
|   | on |     |      | low, | did data augmentation   |     being a  |
|   |    |     |      | ke   | on training generator,  |     cat or   |
|   |    |     |      | ras, | validation generator    |     dog      |
|   |    |     |      | mat  |                         |              |
|   |    |     |      | plot |                         |              |
|   |    |     |      | lib, |                         |              |
|   |    |     |      | sea  |                         |              |
|   |    |     |      | born |                         |              |
+---+----+-----+------+------+-------------------------+--------------+
| D | C  | C   | ANN  | ten  | -   Did some analysis   | -   Given    |
| L | hu | hur |      | sorf |     and preprocessing   |              |
|   | rn | n_m | (84  | low, |     on dataset          |    numerical |
|   | pr | ode | .25) | ke   |                         |              |
|   | ed | lli |      | ras, | -   Created an ANN      |    datapoint |
|   | ic | ng. |      | skle |     blackbox model with |     about a  |
|   | ti | csv |      | arn, |     3 layers and        |              |
|   | on | d   |      | nu   |     trained it with the |    customer, |
|   |    | ata |      | mpy, |     preprocessed        |     the      |
|   |    | set |      | pan  |     dataset             |     model    |
|   |    | f   |      | das, |                         |     predicts |
|   |    | rom |      | ma   | -   Analysed the        |     the      |
|   |    | kag |      | tplo |     accuracy of the     |              |
|   |    | gle |      | tlib |     model               |  probability |
|   |    |     |      |      |                         |     of the   |
|   |    |     |      |      |                         |     customer |
|   |    |     |      |      |                         |              |
|   |    |     |      |      |                         |  terminating |
|   |    |     |      |      |                         |     his/her  |
|   |    |     |      |      |                         |     account  |
|   |    |     |      |      |                         |     from the |
|   |    |     |      |      |                         |     bank     |
+---+----+-----+------+------+-------------------------+--------------+
| D | H  | Mn  | ANN  | ke   | -   Imported dataset    | -   Given    |
| L | an | ist |      | ras, |                         |     pixel    |
|   | dw | d   | (65  | nu   | -   Created a 3 layer   |     values   |
|   | ri | ata | .68) | mpy, |     black box model,    |     in       |
|   | tt | set |      | ma   |     trained using       |     28\*28   |
|   | en | f   |      | tplo |     dataset, error      |              |
|   | d  | rom |      | tlib |     happened due to     |   resoultion |
|   | ig | ke  |      |      |     incompatible shapes |     (B&W) of |
|   | it | ras |      |      |                         |     an image |
|   | r  |     |      |      | -   Reshaped using one  |     of       |
|   | ec |     |      |      |     hot encoding        |              |
|   | og |     |      |      |                         |  handwritten |
|   | ni |     |      |      | -   Trained             |     n        |
|   | ti |     |      |      |     successfully        | umber(single |
|   | on |     |      |      |                         |     digit),  |
|   |    |     |      |      | -   Evaluated the model |     the      |
|   |    |     |      |      |                         |     model    |
|   |    |     |      |      |                         |     will     |
|   |    |     |      |      |                         |     predict  |
|   |    |     |      |      |                         |     the      |
|   |    |     |      |      |                         |     number   |
+---+----+-----+------+------+-------------------------+--------------+
| D | Di | Di  | ANN  | ke   | -   Created an ANN      | -   Given    |
| L | ab | abe |      | ras, |     blackbox model with |     the      |
|   | et | tis | (74  | pan  |     3 layers and        |              |
|   | is | d   | .61) | das, |     trained it with the |    numerical |
|   | pr | ata |      | n    |     dataset             |     data,    |
|   | ed | set |      | umpy |                         |              |
|   | ic | f   |      |      | -   Analysed the        |   determines |
|   | ti | rom |      |      |     accuracy of the     |     the      |
|   | on | Ka  |      |      |     model               |              |
|   |    | ggl |      |      |                         |  probability |
|   |    | e(U |      |      |                         |     that the |
|   |    | SA, |      |      |                         |     patient  |
|   |    | bef |      |      |                         |     has      |
|   |    | ore |      |      |                         |     diabetis |
|   |    | 19  |      |      |                         |     and not  |
|   |    | 90) |      |      |                         |              |
+---+----+-----+------+------+-------------------------+--------------+
| N | Ha | T   | Mu   | skl  | -   Did analysis and    | -   Given    |
| L | te | wit | ltin | earn |     preprocessing       |     comme    |
| P | sp | ter | omia | and  |                         | nt/sentence, |
|   | ee | d   | lNB, | o    | -   Applied Regex to    |     the      |
|   | ch | ata | Ra   | ther |     clean data          |     model    |
|   | d  |     | ndom | data |                         |     will     |
|   | et |     | fo   | anal | -   Applied             |     predict  |
|   | ec |     | rest | ysis |     oversampling        |     if it is |
|   | ti |     | cla  | l    |     (random)            |     hate     |
|   | on |     | ssif | ibra |                         |     speech   |
|   |    |     | ier, | ries | -   Applied             |     or not   |
|   |    |     | XG   |      |     Tfidftransformer to |     (1 if    |
|   |    |     | Bcla |      |     xtrain after        |     hate     |
|   |    |     | ssif |      |     applying            |     speech,  |
|   |    |     | ier, |      |     Count-vectorizer    |     0 if     |
|   |    |     | SVM, |      |                         |     not)     |
|   |    |     | Logi |      | -   Did multiple        |              |
|   |    |     | stic |      |     algorithms and      |              |
|   |    |     | re   |      |     analysed each       |              |
|   |    |     | gres |      |     model's F1 score    |              |
|   |    |     | sion |      |                         |              |
|   |    |     |      |      | -   Analysed ROC curve, |              |
|   |    |     |      |      |     Precision-recall    |              |
|   |    |     |      |      |     curve for Random    |              |
|   |    |     |      |      |     forest and XGBoost  |              |
+---+----+-----+------+------+-------------------------+--------------+
| N | S  | Sen | Mul  | skle | -   Did some analysis   | -   Given a  |
| L | en | tim | tino | arn, |     on dataset          |     review   |
| P | ti | ent | mial | pan  |                         |     that was |
|   | me | an  | n    | das, | -   Applied             |              |
|   | nt | aly | aive | ma   |     Tfidfvectorizer     | preprocessed |
|   | an | sis | b    | tplo |                         |     with     |
|   | al | of  | ayes | tlib | -   Fitted the model    |     Tfid     |
|   | ys | mo  |      |      |                         | fvectorizer, |
|   | is | vie | (58  |      | -   Tested the model    |     the      |
|   | u  | r   | .65) |      |                         |     model    |
|   | si | evi |      |      |                         |     will     |
|   | ng | ews |      |      |                         |     predict: |
|   | te | d   |      |      |                         |     0 if     |
|   | xt | ata |      |      |                         |              |
|   | cl | set |      |      |                         |    negative, |
|   | as | f   |      |      |                         |     1 if     |
|   | si | rom |      |      |                         |     somewhat |
|   | fi | Kag |      |      |                         |              |
|   | ca | gle |      |      |                         |    negative, |
|   | ti |     |      |      |                         |     2 if     |
|   | on |     |      |      |                         |     neutral, |
|   |    |     |      |      |                         |     3 if     |
|   |    |     |      |      |                         |     somewhat |
|   |    |     |      |      |                         |              |
|   |    |     |      |      |                         |    positive, |
|   |    |     |      |      |                         |     4 if     |
|   |    |     |      |      |                         |     positive |
+---+----+-----+------+------+-------------------------+--------------+
| N | E  | Sm  | Mul  | skle | -   Preprocessed        | -            |
| L | ma | ssp | tino | arn, |     dataset with        |   Preprocess |
| P | il | amc | mial | job  |     Encoding,           |     a sample |
|   | sp | oll | n    | lib, |     Countvectorizer,    |     into     |
|   | am | ect | aive | pan  |     Random sampling     |     cou      |
|   | cl | ion | b    | das, |                         | ntvectorizer |
|   | as | d   | ayes | imbl | -   Fitted the model    |     feed to  |
|   | si | ata |      | earn |                         |     model    |
|   | fi | set | (WA  |      | -   Analysed the model  |     and the  |
|   | ca |     | of   | (add |     with Classification |     model    |
|   | ti |     | f1=0 | d    |     matrix              |     will     |
|   | on |     | .98) | etai |                         |     predict  |
|   |    |     |      | ls?) | -   Converted the model |     if it is |
|   |    |     |      |      |     to Joblib format    |     a spam   |
|   |    |     |      |      |     and saved to file   |     comment  |
|   |    |     |      |      |                         |     or not   |
+---+----+-----+------+------+-------------------------+--------------+
| C | Fa | S   | HAAR | cv2, | -   Created folders     | -   selfie   |
| o | ce | elf | cas  | os,  |     'id' and 'name'     |              |
| m | de | m   | cade | csv, |                         |              |
| p | te | ade | pr   | nu   | -   Took face samples   |              |
| u | ct | d   | etra | mpy, |     directly from video |              |
| t | or | ata | ined | PIL, |     feed detected by    |              |
| e | &  | a   | mo   | pa   |     HAAR cascade        |              |
| r | re | ppl | del, | ndas |     detector and stored |              |
| v | co | ied | LBPH |      |     as file             |              |
| i | gn | on  | face |      |                         |              |
| s | iz | p   | re   |      | -   Created a           |              |
| i | er | ret | cogn |      |     subdirectory for    |              |
| o |    | rai | izer |      |     trainer data,       |              |
| n |    | ned |      |      |     cropped out the     |              |
|   |    | mod |      |      |     faces using haar,   |              |
|   |    | els |      |      |     trained using LBPH  |              |
|   |    |     |      |      |     Recognizer          |              |
|   |    |     |      |      |                         |              |
|   |    |     |      |      | -   Saved the trained   |              |
|   |    |     |      |      |     model(yml file)     |              |
|   |    |     |      |      |     into                |              |
|   |    |     |      |      |                         |              |
|   |    |     |      |      |  subdirectory,'trainer' |              |
|   |    |     |      |      |                         |              |
|   |    |     |      |      | -   Tested the model    |              |
|   |    |     |      |      |     with opening        |              |
|   |    |     |      |      |     Camera,             |              |
|   |    |     |      |      |     preprocessed the    |              |
|   |    |     |      |      |     feed, and analysed  |              |
|   |    |     |      |      |     using c-Confidence  |              |
|   |    |     |      |      |     of the Recognizer.  |              |
+---+----+-----+------+------+-------------------------+--------------+
| M | Cu | Ma  | K-m  | skle | -   Feature engineered  | -   Given    |
| L | st | ll_ | eans | arn, |     necessary columns   |     income,  |
|   | om | cus | clu  | pan  |                         |     it will  |
|   | er | tom | ster | das, | -   Fitted K-means      |     predict  |
|   | se | ers | ing, | mat  |     algorithm 10 times  |     the      |
|   | gm | d   | DB   | plot |     with 10 values      |     cluster  |
|   | en | ata | SCAN | lib, |                         |     the      |
|   | ta | set | clu  | nu   | -   Plotted elbow       |     person   |
|   | ti | f   | ster | mpy, |     method graph (wcss  |     is part  |
|   | on | rom | ing, | math |     list vs number of   |     of       |
|   |    | Kag | A    |      |     clusters) and chose |              |
|   |    | gle | gglo |      |     optimum number of   |              |
|   |    |     | mera |      |     clusters            |              |
|   |    |     | tive |      |                         |              |
|   |    |     | clu  |      | -   Visualised clusters |              |
|   |    |     | ster |      |                         |              |
|   |    |     | ing, |      | -   Used nearest        |              |
|   |    |     | Hier |      |     neighbors to        |              |
|   |    |     | arch |      |     determine optimum   |              |
|   |    |     | ical |      |     parameters with     |              |
|   |    |     | cl   |      |     K-distance graph,   |              |
|   |    |     | uste |      |     fitted on DBSCAN    |              |
|   |    |     | ring |      |     and visualised the  |              |
|   |    |     |      |      |     clusters            |              |
|   |    |     |      |      |                         |              |
|   |    |     |      |      | -   Fitted              |              |
|   |    |     |      |      |     Agglomerative and   |              |
|   |    |     |      |      |     Hierarchical        |              |
|   |    |     |      |      |     clustering          |              |
|   |    |     |      |      |     additionally        |              |
+---+----+-----+------+------+-------------------------+--------------+
| M | Ma | 7   | Apr  | apy  | -   Analysed and        | -   The      |
| L | rk | 500 | iori | ori, |     preprocessed data   |     model    |
|   | et | tra |      | nu   |     into list for       |     created  |
|   | ba | nsa |      | mpy, |     Apriori algorithm   |     some     |
|   | sk | cti |      | pan  |                         |     rules.   |
|   | et | ons |      | das, | -   Fitted Apriori      |     You can  |
|   | an | of  |      | ma   |     model with required |     analyse  |
|   | al | a   |      | tplo |     parameters          |     the      |
|   | ys | w   |      | tlib |                         |     relatons |
|   | is | eek |      |      | -   Derived relations   |     of items |
|   | of | at  |      |      |                         |     with     |
|   | s  | a   |      |      | -   Derived rules       |     other    |
|   | to | Fre |      |      |                         |     items.   |
|   | re | nch |      |      |                         |              |
|   | da | ret |      |      |                         |              |
|   | ta | ail |      |      |                         |              |
|   |    | st  |      |      |                         |              |
|   |    | ore |      |      |                         |              |
+---+----+-----+------+------+-------------------------+--------------+
| M | Ir | I   | Deci | mat  | -   Performed data      | -   Given    |
| L | is | ris | sion | plot |     analysis and        |              |
|   | mu | da  | tree | lib, |     visualisation on    |  indipendent |
|   | lt | tas | s(0. | seab |     dataset             |              |
|   | ic | et( | 93), | orn, |                         |   variables, |
|   | la | the | KN   | pan  | -   Trained decision    |     models   |
|   | ss | cha | N(0. | das, |     tree model,         |     will     |
|   | cl | rac | 93), | n    |     visualised tree,    |     predict  |
|   | as | ter | Ra   | umpy |     evaluated,          |     the      |
|   | si | ist | ndom |      |     hyperparameter      |     class    |
|   | fi | ics | f    |      |     tuned with K fold   |     the      |
|   | ca | of  | ores |      |     and GridSearchCV    |     sample   |
|   | ti | e   | t(0. |      |                         |              |
|   | on | ach | 93), |      | -   Trained KNN, Random |    datapoint |
|   |    | i   | Grad |      |     forest, Gradient    |     belongs  |
|   |    | ris | ient |      |     boosting regressor  |     in.      |
|   |    | s   | boos |      |     models              |              |
|   |    | pec | ting |      |                         |              |
|   |    | ies | reg  |      | -   Hyperparameter      |              |
|   |    | fl  | ress |      |     tuned the above     |              |
|   |    | owe | or(0 |      |     models              |              |
|   |    | rs) | .93) |      |                         |              |
|   |    |     |      |      | -   Evaluated the above |              |
|   |    |     |      |      |     models with         |              |
|   |    |     |      |      |     multilabel          |              |
|   |    |     |      |      |     confusion matrix    |              |
|   |    |     |      |      |     and classification  |              |
|   |    |     |      |      |     report.             |              |
+---+----+-----+------+------+-------------------------+--------------+
| M | Br | Bre | Logi | skle | -   Dataset splitted    | -   Given    |
| L | ea | ast | stic | arn, |     into train and test |              |
|   | st | can | reg  | mat  |                         |  indipendent |
|   | ca | cer | ress | plot | -   Scaled independent  |              |
|   | nc | d   | ion, | lib, |     variables           |   variables, |
|   | er | ata | SVM, | pa   |                         |     models   |
|   | pr | set | KNN, | ndas | -   Trained models of   |     will     |
|   | ed |     | Deci |      |     Logistic            |     predict  |
|   | ic |     | sion |      |     regression, SVM,    |     the      |
|   | ti |     | t    |      |     KNN, Decision tree, |     class    |
|   | on |     | ree, |      |     Naive bayes         |     the      |
|   |    |     | N    |      |                         |     sample   |
|   |    |     | aive |      | -   Evaluated all the   |              |
|   |    |     | b    |      |     models and visually |    datapoint |
|   |    |     | ayes |      |     compared the        |     belongs  |
|   |    |     |      |      |     classification      |     in.      |
|   |    |     |      |      |     report. Logistic    |              |
|   |    |     |      |      |     regression have the |              |
|   |    |     |      |      |     most overall        |              |
|   |    |     |      |      |     performance at the  |              |
|   |    |     |      |      |     moment              |              |
+---+----+-----+------+------+-------------------------+--------------+
| M | Pr | T   | Logi | skle | -   Analysed and        | -   given    |
| L | ed | ita | stic | arn, |     preprocessed the    |     the      |
|   | ic | nic | re   | pa   |     datset with Pandas  |              |
|   | ti | d   | gres | ndas |                         |  indipendent |
|   | ng | ata | sion |      | -   Dataset splitted    |              |
|   | su | set | (79  |      |     into train and test |    variables |
|   | rv |     | .88) |      |                         |     of       |
|   | iv |     |      |      | -   Fitted Logistic     |              |
|   | al |     |      |      |     regression          |   passengers |
|   | T  |     |      |      |                         |     in       |
|   | it |     |      |      | -   Analysed the model  |     Titanic  |
|   | an |     |      |      |     by evaluating the   |     dataset, |
|   | ic |     |      |      |     accuracy score      |     it will  |
|   | pa |     |      |      |                         |     predict  |
|   | ss |     |      |      |                         |     whether  |
|   | en |     |      |      |                         |     they     |
|   | ge |     |      |      |                         |     survive  |
|   | rs |     |      |      |                         |     or not   |
+---+----+-----+------+------+-------------------------+--------------+
| M | Pr | SUV | Logi | skle | -   Analysed and        | -   Given    |
| L | ed | dat | stic | arn, |     preprocessed        |     the      |
|   | ic | ase | re   | pan  |     dataset             |              |
|   | ti | t(w | gres | das, |                         |  indipendent |
|   | ng | het | sion | mat  | -   Logistic model is   |              |
|   | pu | her |      | plot |     created and fitted  |    variables |
|   | rc | the | (WA= | lib, |                         |     of       |
|   | ha | cu  | 0    | sea  | -   Analysed with       |              |
|   | se | sto | .83) | born |     Classification      |   customers, |
|   |    | mer |      |      |     matrix              |     the      |
|   |    | b   |      |      |                         |     model    |
|   |    | uys |      |      | -   Plotted Roc-auc     |     will     |
|   |    | SUV |      |      |     curve               |     predict  |
|   |    | or  |      |      |                         |     whether  |
|   |    | n   |      |      | -   Calculatted Log     |     they     |
|   |    | ot) |      |      |     loss(0.39)          |     will buy |
|   |    |     |      |      |                         |     the car  |
|   |    |     |      |      |                         |     or not   |
+---+----+-----+------+------+-------------------------+--------------+
| M | B  | H   | Li   | skle | -   Splitted dataset    | -   Given    |
| L | ra | ead | near | arn, |     into train-test     |     input    |
|   | in | bra | re   | nu   |                         |              |
|   | we | in. | gres | mpy, | -   Fitted into Linear  |   variables, |
|   | ig | csv | sion | pa   |     regression model    |     model    |
|   | ht |     |      | ndas |                         |     will try |
|   | pr |     | (    |      | -   Evaluated score     |     to       |
|   | ed |     | R2=0 |      |                         |     predict  |
|   | ic |     | .63) |      |                         |     a value  |
|   | ti |     |      |      |                         |              |
|   | on |     |      |      |                         |              |
+---+----+-----+------+------+-------------------------+--------------+
| M | Po | H   | Po   | skle | -   Converted data into | -   Given    |
| L | ly | ead | lyno | arn, |     input and output    |     input    |
|   | no | bra | mial | nu   |                         |              |
|   | mi | in. | re   | mpy, | -   Standardized        |   variables, |
|   | al | csv | gres | pan  |     indipendent values  |     model    |
|   | re |     | sion | das, |                         |     will try |
|   | gr |     | wit  | ma   | -   Executed program    |     to       |
|   | es |     | hout | tplo |     and Regrerssion     |     predict  |
|   | si |     | dot  | tlib |     line visualized     |     a value  |
|   | on |     | pro  |      |                         |              |
|   | fr |     | duct |      | -   Evaluated model     |              |
|   | om |     |      |      |     with                |              |
|   | s  |     | (    |      |     Error-iteration     |              |
|   | cr |     | R2=0 |      |     plot                |              |
|   | at |     | .58) |      |                         |              |
|   | ch |     |      |      | -   Calculated R2 score |              |
|   | wi |     |      |      |                         |              |
|   | to |     |      |      |                         |              |
|   | ut |     |      |      |                         |              |
|   | v  |     |      |      |                         |              |
|   | ec |     |      |      |                         |              |
|   | to |     |      |      |                         |              |
|   | ri |     |      |      |                         |              |
|   | za |     |      |      |                         |              |
|   | ti |     |      |      |                         |              |
|   | on |     |      |      |                         |              |
+---+----+-----+------+------+-------------------------+--------------+
| D | FB |     |      |      | -                       | -            |
| a | p  |     |      |      |                         |              |
| t | os |     |      |      |                         |              |
| a | ts |     |      |      |                         |              |
| A | an |     |      |      |                         |              |
| n | al |     |      |      |                         |              |
| a | ys |     |      |      |                         |              |
| l | is |     |      |      |                         |              |
| y |    |     |      |      |                         |              |
| s |    |     |      |      |                         |              |
| i |    |     |      |      |                         |              |
| s |    |     |      |      |                         |              |
+---+----+-----+------+------+-------------------------+--------------+
| D | T  |     |      |      | -                       | -            |
| a | it |     |      |      |                         |              |
| t | an |     |      |      |                         |              |
| a | ic |     |      |      |                         |              |
| A | d  |     |      |      |                         |              |
| n | at |     |      |      |                         |              |
| a | as |     |      |      |                         |              |
| l | et |     |      |      |                         |              |
| y | an |     |      |      |                         |              |
| s | al |     |      |      |                         |              |
| i | ys |     |      |      |                         |              |
| s | is |     |      |      |                         |              |
+---+----+-----+------+------+-------------------------+--------------+
| D | 'T |     |      |      | -                       | -            |
| a | im |     |      |      |                         |              |
| t | es |     |      |      |                         |              |
| a | of |     |      |      |                         |              |
| A | I  |     |      |      |                         |              |
| n | nd |     |      |      |                         |              |
| a | ia |     |      |      |                         |              |
| l | 'N |     |      |      |                         |              |
| y | ew |     |      |      |                         |              |
| s | sp |     |      |      |                         |              |
| i | ap |     |      |      |                         |              |
| s | er |     |      |      |                         |              |
|   | an |     |      |      |                         |              |
|   | al |     |      |      |                         |              |
|   | ys |     |      |      |                         |              |
|   | is |     |      |      |                         |              |
+---+----+-----+------+------+-------------------------+--------------+
