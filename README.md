# startlearning
Code to translate the DNA sequence to a sequence of Amino acids where each Amino acid is
   represented by a unique letter
    } 
    protein ="" 
    if len(seq)%3 == 0: 
        for i in range(0, len(seq), 3): 
            codon = seq[i:i + 3] 
            protein+= table[codon] 
    return protein 
   
