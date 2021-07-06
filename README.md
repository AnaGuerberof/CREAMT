# CREAMT
CREAMT: https://cordis.europa.eu/project/id/890697

The data for the 1st axis is: Acceptability, Creative Shifts, Pre-task and post-task questionnaires for reviewers and translators, TER, PET, Interview transcripts.


Acceptability
  String_Id corresponds to a sentence so you will see that if there is more than one error, the ID is repeated.
  paragraph_id corresponds to the paragraph where the sentence is (the translators translated by paragraph and so it was interesting to me).
  rev the reviewer, there are 3, 3 Catalans and 2 Dutch.
  tr the translators, nor has 4 and 2 machines.
  modality if the translation was done by the machine, a translator corrected it (mtpe) or a translator did it without anything (ht)
  error_category the type of error
  error_subcategory the type of error within the main category
  error_severity the severity of the error. Critical 10 points, Major 5 points, Minor 1 point, Neutral 0 points
  language the language
  error_number counts if any error is marked
  error_points adds the severity of the error
  kudos marks that this sentence was very well translated
  
Creative Shifts
  String_Id corresponds to a sentence so you will see that if there is more than one creative shift, the ID is repeated.
  paragraph_id corresponds to the paragraph where the sentence is (the translators translated by paragraph and so it was interesting to me).
  ucp Unit of creative potential corresponds to the unit for which we look for if there is creative shift.
  source_paragraph the original text
  attached the text of the ucp
  modality if the translation was done by the machine, a translator corrected it (mtpe) or a translator did it without anything (ht)
  rev the reviewer, there are 3, 3 Catalans and 2 Dutch.
  tr the translators, nor has 4 and 2 machines.
  classification indicates whether there is a Creative shift, Reproduction, Omission or NA
  sub_classification indicates the type of creative shift, reproduction, omission or na.
  language the language
  reproduction indicates whether there is reproduction or not
  omission indicates whether there is omission or not
  creative shift indicates whether there is Modification, Abstraction or Concretization
  NA indicates that it could not be classified because there are too many errors
