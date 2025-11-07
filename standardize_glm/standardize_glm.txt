# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Get regression standardized estimates from a glm Use standardize_glm (stdReg2) With (In) R Software
install.packages("stdReg2")
library("stdReg2")
standardize_glm = read.csv("https://raw.githubusercontent.com/timbulwidodostp/standardize_glm/main/standardize_glm/standardize_glm.csv",sep = ";")
# Estimation Get regression standardized estimates from a glm Use standardize_glm (stdReg2) With (In) R Software
standardize_glm <- standardize_glm(formula = Y ~ X * Z, family = "binomial", data = standardize_glm, 
values = list(X = c("low", "high")), contrasts = c("difference", "ratio"), reference = "low")
standardize_glm
# Get regression standardized estimates from a glm Use standardize_glm (stdReg2) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished