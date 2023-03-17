csv2sid transposes an exisiting sid file by changing the SID values inside by those stored in a CSV file. This can be used when manual allocation of SIDs is needed.

CSV follows the format specified in https://datatracker.ietf.org/doc/draft-bormann-cbor-cddl-csv/

syntax:
 csv2sid csv_file input_sid output_sid
 
 Transposition is done only if all the identifiers contained in the input_sid file are found in the CSV
