Flag-based jumps

The jumps based on the flags being set/reset are:
Instruction 	Description
JZ shortlabel	jump if zero
JNZ shortlabel	jump if not zero
JS shortlabel	jump if sign
JNS shortlabel	jump if not sign
JC shortlabel	jump if carry
JNC shortlabel	jump if not carry
JO shortlabel	jump if overflow
JNO shortlabel	jump if not overflow
JP shortlabel	jump if parity
JNP shortlabel	jump if not parity
JPE shortlabel	jump if parity even
JPO shortlabel	jump if parity odd

Signed Conditional Jumps

Instruction 	Symbolic 	Description
JE shortlabel	op1 = op2 	jump if equal
JNE shortlabel	op1 != op2 	jump if not equal
JG shortlabel	op1 > op2 	jump if greater than
JNG shortlabel	!(op1 > op2) 	jump if not greater than
JGE shortlabel	op1 >= op2 	jump if greater than or equal
JNGE shortlabel	!(op1 >= op2) 	jump if not greater than or equal
JL shortlabel	op1 < op2 	jump if less than
JNL shortlabel	!(op1 < op2) 	jump if not less than
JLE shortlabel	op1 <= op2 	jump if less than or equal
JNLE shortlabel	!(op1 <= op2) 	jump if not less than or equal
