# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fit Generalized Linear Mixed Models via Penalized Quasi-Likelihood (PQL) Use glmmPQL (MASS) With (In) R Software
install.packages("MASS")
library("MASS")
glmmPQL = read.csv("https://raw.githubusercontent.com/timbulwidodostp/glmmPQL/main/glmmPQL/glmmPQL.csv",sep = ";")
# Estimation Fit Generalized Linear Mixed Models via Penalized Quasi-Likelihood (PQL) Use glmmPQL (MASS) With (In) R Software
glmmPQL <- glmmPQL(glmmPQL ~ glmmPQL_1 + I(glmmPQL_2 > 2), random = ~ 1 | ID, family = binomial, data = glmmPQL)
summary(glmmPQL)
# Fit Generalized Linear Mixed Models via Penalized Quasi-Likelihood (PQL) Use glmmPQL (MASS) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished