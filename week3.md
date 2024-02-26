my_vector <- c(1, 2, 3, 4, 5)
reversed_vector <- rev(my_vector)
cat("Original Vector:", my_vector, "\n")
cat("Reversed Vector:", reversed_vector, "\n")
vector1 <- c(1, 2, 3)
vector2 <- c(4, 5, 6)
concatenated_vector <- c(vector1, vector2)
cat("Vector 1:", vector1, "\n")
cat("Vector 2:", vector2, "\n")
cat("Concatenated Vector:", concatenated_vector, "\n")
my_vector <- c(5, 10, 15, 20, 25, 30)
count_in_range <- sum(my_vector > 10 & my_vector < 20)
cat("Vector:", my_vector, "\n")
cat("Count in Range (10, 20):", count_in_range, "\n")
my_vector <- c(5, 12, 8, 15, 20)
greater_than_10 <- my_vector > 10
cat("Vector:", my_vector, "\n")
cat("Values Greater than 10:", greater_than_10, "\n")
my_list <- list(
  my_vector = c(1, 2, 3),
  my_matrix = matrix(1:4, nrow = 2),
  my_nested_list = list("A", "B", "C")
)
first_element <- my_list[[1]]
second_element <- my_list[[2]]
cat("List:", my_list, "\n")
cat("First Element:", first_element, "\n")
cat("Second Element:\n", second_element, "\n")
my_list <- list(
  my_vector = c(1, 2, 3),
  my_matrix = matrix(1:4, nrow = 2),
  my_nested_list = list("A", "B", "C")
)
my_list$additional_element <- "New Element"
cat("Updated List:\n", my_list, "\n")
nested_list <- list(c(1, 2, 3), c("A", "B", "C"), list(TRUE, FALSE))
second_element <- nested_list[[2]]
cat("Nested List:\n", nested_list, "\n")
cat("Second Element:", second_element, "\n")
vector1 <- c(1, 2, 3)
vector2 <- c(4, 5, 6)
my_matrix <- matrix(c(vector1, vector2), nrow = 2, byrow = TRUE)
cat("Matrix:\n", my_matrix, "\n")
my_matrix <- matrix(1:9, nrow = 3)
my_array <- as.vector(my_matrix)
cat("Matrix:\n", my_matrix, "\n")
cat("1-dimensional Array:", my_array, "\n")
vector1 <- c(1, 2, 3, 4, 5, 6, 7, 8, 9)
vector2 <- c(9, 8, 7, 6, 5, 4, 3, 2, 1)
my_array <- array(c(vector1, vector2), dim = c(3, 3, 2))
cat("Array:\n", my_array, "\n")
vector1 <- c(1, 2, 3, 4, 5, 6, 7, 8, 9)
vector2 <- c(9, 8, 7, 6, 5, 4, 3, 2, 1)
my_array <- array(c(vector1, vector2), dim = c(3, 3, 2))
second_row_second_matrix <- my_array[2, , 2]
element_3_3_first_matrix <- my_array[3, 3, 1]
cat("Array:\n", my_array, "\n")
cat("Second Row of Second Matrix:", second_row_second_matrix, "\n")
cat("Element at 3rd Row, 3rd Column of 1st Matrix:", element_3_3_first_matrix, "\n")
my_data_frame <- data.frame(
  Name = c("Alice", "Bob", "Charlie"),
  Age = c(25, 30, 22),
  Weight = c(65, 70, 68),
  Height = c(170, 175, 160)
  )
summary_stats <- summary(my_data_frame)
data_structure <- str(my_data_frame)
cat("Data Frame:\n", my_data_frame, "\n")
cat("Summary Stats:\n", summary_stats, "\n")
cat("Data Structure:\n", data_structure, "\n")
my_data_frame <- data.frame(
  Name = c("Alice", "Bob", "Charlie"),
  Age = c(25, 30, 22),
  Weight = c(65, 70, 68),
  Height = c(170, 175, 160)
)
selected_data <- my_data_frame[c(3, 5), c(1, 3)]
cat("Data Frame:\n", my_data_frame, "\n")
cat("Selected Data:\n", selected_data, "\n")
my_data_frame <- data.frame(
  Name = c("Alice", "Bob", "Charlie"),
  Age = c(25, 30, 22),
  Weight = c(65, 70, 68),
  Height = c(170, 175, 160)
)
new_row <- c("David", 28, 72, 180)
my_data_frame <- rbind(my_data_frame, new_row)
new_column <- c("Female", "Male", "Male", "Male")
my_data_frame$Gender <- new_column
cat("Updated Data Frame:\n", my_data_frame, "\n")

