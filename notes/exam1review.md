### Exam 1 - Topics & Review
#### **god help me on this one**

- format
  - 5 TF
  - 5 MC
  - short to medium answer (12 total)
  - program
    - no code writing, but understanding what a program does
  - diagram labeling
- 50 minute test
- content up to lecture 10, slide 12

- simple memory system TLB
  - ex. 14-bit address `000011 01 000010` (tag, index, offset), 4-way set associative cache
  - enter set `01` (from index)
  - check for PTE `000011 = 0x03`
  - if PTE valid bit = 1, then TLB hit
    - say that we do hit - stored value of `0x2D`
  - physical page number is given by `2D` + `000010` (offset) = `0010 1101 000010`
  - 