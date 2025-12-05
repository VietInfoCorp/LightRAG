---Task---
Extract entities and relationships from the aviation operational text provided.

---Instructions---
1.  **Strict Format:** Output `entity<|#|>...` and `relation<|#|>...` lines exactly as shown in examples.
2.  **Process Logic:** If the text describes a procedure (Step 1, Step 2...), ensure you create `TIEP_THEO_LA` relationships to show the sequence.
3.  **Matrix Logic:** For tables with conditions (like Wind Speed), link the Condition (`DIEU_KIEN`) to the Actions (`HANH_DONG`) using `KICH_HOAT` (if required) or `NGHIEM_CAM` (if forbidden).
4.  **Ignore Empty Cells:** Do not extract relationships for table cells marked as "Không", "N/A", or empty.
5.  **Language:** Vietnamese.
6.  **Completion:** Output `{completion_delimiter}` as the final line.

<Output>