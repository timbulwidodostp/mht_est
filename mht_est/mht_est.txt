# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Apply multiple hypothesis testing (MHT) Testing Directly to a Fitted Model (Postestimation) Use mht_est (mhtopt) With (In) R Software
install.packages("mhtopt")
library("mhtopt")
# Estimate Apply multiple hypothesis testing (MHT) Testing Directly to a Fitted Model (Postestimation) Use mht_est (mhtopt) With (In) R Software
mht_est = read.csv("https://raw.githubusercontent.com/timbulwidodostp/mht_est/main/mht_est/mht_est.csv",sep = ";")
mht_est_ <- lm(mht_est ~ mht_est_1 + mht_est_2 + mht_est_3 + mht_est_4 + mht_est_5 + mht_est_6+ mht_est_7 + mht_est_8, data = mht_est)
mht_est <- mht_est(mht_est_, vars = c("mht_est_1", "mht_est_2", "mht_est_3", "mht_est_4", "mht_est_5", "mht_est_6", "mht_est_7", "mht_est_8"), alpha_bar = 0.05)
mht_est
# Apply multiple hypothesis testing (MHT) Testing Directly to a Fitted Model (Postestimation) Use mht_est (mhtopt) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished