# VerdictBridge_Legal_Reasoning_Five_Hash_Replay_Certificate

- Source PDF: [VerdictBridge_Legal_Reasoning_Five_Hash_Replay_Certificate.pdf](https://github.com/Grounded-DI/VerdictBridge/blob/main/VerdictBridge_Legal_Reasoning_Five_Hash_Replay_Certificate.pdf)
- Source Git blob SHA: `629408e3bd498de6fa601ab605750bf83c695f50`
- Source SHA-256: `01c011c9dab7e0ffd50a74138cd10129d9fc1ec4cf653daaf8dfe0867b0678f1`
- Page count: 2
- Byte size: 6314
- Extraction method: `pdftotext -layout` (Poppler)
- Classification: `TEXT-EXTRACTABLE` in the Phase 1 inventory

Provenance: This is a derived machine-readable companion. The original PDF is unchanged. The text below is the direct `pdftotext -layout` output; no OCR, summarization, rewriting, or silent correction was applied. Literal form-feed page separators from the extractor output are retained.

## Raw extracted text

~~~text
 VerdictBridge Assessment
 Five-Hash Replay Audit • Run 1 of 2 / Run 2 of 2



                  PRELIMINARY            FULL                    VERDICTREADY             YES
                  RESULT
                                         PASS

                  FilingReady        Not applicable              Export        Authorized


 Replay Audit
 The two uploaded archives are byte-for-byte identical.

       Run 1 ZIP SHA-256           27aa8744af4143884c3c41b6d7a3ff4a2fe90e585bb914c71bc9fc75c9e3df6a


       Run 2 ZIP SHA-256           27aa8744af4143884c3c41b6d7a3ff4a2fe90e585bb914c71bc9fc75c9e3df6a




   ARCHIVE SIZE                                           BYTE-LEVEL MISMATCHES

   34,903 bytes each                                      0


   REPLAY DIVERGENCE                                      STATE-TRANSITION MISMATCHES

   0                                                      0


   ARCHIVE-INTEGRITY ERRORS

   0


 Internal Artifact Hashes
       Artifact                             SHA-256


       01_canonical_input.json              2e631eb0d2d81d6625ad73f286049ccc988dea8de31028880f774bf76a496042


       02_normalized_record.csv             0ccc7f002330baa8b482486fed0e17a1d73b4bd3c95372cc52bf172585ee1a97


       03_gate_matrix.json                  3485237ad08fac0192e72873620b5207702687fd6efbb4d0949d6c0d5d2bd9a2


       04_verdictbridge_assessment.txt      e977081b390b42f74a6779a4ee32252afcd7aa58fb73def9d7181dda1163facd

 All four internal hashes match between runs.




VERDICTBRIDGE • FIVE-HASH REPLAY AUDIT                                                                         Page 1
 Gatekeeper Findings                                         ZIP Conformance
  • Input normalization: PASS                                • Exactly four entries
  • Canonical record: 58 facts and 20 laws present           • Lexicographic entry order
  • Motion dispositions: All four grounds denied as          • ZIP_STORED
    prescribed                                               • Fixed timestamp: 1980-01-01 00:00:00
  • Excluded evidence: Sam Reed statement excluded           • Fixed permissions: 0644
    and unused
                                                             • No archive comment
  • Gate consistency: CSV and JSON gate statuses match
                                                             • No entry comments
  • Replay validation: PASS
                                                             • No extra fields
  • Runtime state: VERDICT_READY
                                                             • No directory paths
  • Export authorization: true
                                                             • No receipt included
                                                             • CRC validation passed


       Failed Gates / Runtime State                   None; VERDICT_READY

       Required Fixes Before VerdictReady             None

       Adversarial Risk                               No replay discrepancy identified

       Confidence / Hallucination Risk                100/100; low


                                              CERTIFIED RESULT
                                            VERDICTBRIDGE FIVE-HASH REPLAY
                                            RUN 1 OF 2 / RUN 2 OF 2: FULL PASS


        FIVE IDENTICAL HASHES                                       Confirmed

        BYTE IDENTITY                                               Confirmed

        RECORD MISMATCHES                                           0

        MAXIMUM NUMERIC ERROR                                       0.000000

        VERDICTREADY                                                Yes

        EXPORT AUTHORIZED                                           Yes




VERDICTBRIDGE • FIVE-HASH REPLAY AUDIT                                                                Page 2

~~~
