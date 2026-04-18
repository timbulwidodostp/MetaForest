# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Conduct a MetaForest analysis to explore heterogeneity in meta-analytic data Use MetaForest (metaforest) With (In) R Software
install.packages("metaforest")
library("metaforest")
# Estimation Conduct a MetaForest analysis to explore heterogeneity in meta-analytic data Use MetaForest (metaforest) With (In) R Software
MetaForest = read.csv("https://raw.githubusercontent.com/timbulwidodostp/MetaForest/main/MetaForest/MetaForest.csv",sep = ";")
MetaForest <- MetaForest(formula = yi ~ ., data = MetaForest, whichweights = "unif")
summary(MetaForest)
# Conduct a MetaForest analysis to explore heterogeneity in meta-analytic data Use MetaForest (metaforest) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished