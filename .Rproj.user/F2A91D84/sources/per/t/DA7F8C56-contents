data1 <- read.table("(6)1.csv",header = TRUE, sep =",")
data1
data1$i <- NULL 
fm <- lm(YZ ~ ., data = data1)
summary(fm)
slm1 <- step(fm)