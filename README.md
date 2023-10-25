# ExpoDecay-LogGrowth_graphs

## Exponential decay
decay_rate <- 0.05  # Decay rate, adjust as needed
initial_value <- 100  # Initial value, adjust as needed
time <- seq(0, 100, by = 1)  # Time values from 0 to 100 (adjust as needed)

### Calculate the values for the exponential decay
decay_values <- initial_value * exp(-decay_rate * time)

### Create the plot
plot(time, decay_values, type = "l", xlab = "Time", ylab = "Value",
     main = "Exponential Decay", col = "blue")

### Add a grid
grid()

<img width="227" alt="image" src="https://github.com/sherlynette/ExpoDecay-LogGrowth_graphs/assets/11760597/5936af70-130e-49c1-9065-747f507c9d78">


## Logarithmic growth
growth_rate <- 0.05  # Growth rate, adjust as needed
initial_value <- 1  # Initial value, adjust as needed
time <- seq(0, 10, by = 0.1)  # Time values from 0 to 10 (adjust as needed)

### Calculate the values for logarithmic growth
growth_values <- initial_value + growth_rate * log(time)

### Create the plot
plot(time, growth_values, type = "l", xlab = "Time", ylab = "Value",
     main = "Logarithmic Growth", col = "green")

     <img width="233" alt="image" src="https://github.com/sherlynette/ExpoDecay-LogGrowth_graphs/assets/11760597/e924f7e8-66f9-41f2-8b5b-a012ab1e99a6">


    


