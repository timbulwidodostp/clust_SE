# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Cluster robust standard errors with degrees of freedom adjustments (for lm and glm objects) Use clustSE (CR2) With (In) R Software
install.packages("CR2")
library("CR2")
require(lme4)
clust_SE = read.csv("https://raw.githubusercontent.com/timbulwidodostp/clust_SE/main/clust_SE/clust_SE.csv",sep = ";")
# Estimation Cluster robust standard errors with degrees of freedom adjustments (for lm and glm objects) Use clustSE (CR2) With (In) R Software
clustSE(lm(Dependen ~ Independen_1 + Independen_2, data = clust_SE), 'Group')
# Cluster robust standard errors with degrees of freedom adjustments (for lm and glm objects) Use clustSE (CR2) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished