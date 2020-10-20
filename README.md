# Jing-Hao_MCQ-revision-program
This is a MCQ revision for biology
print("Title of program: MCQ revision program")
print()

counter = 0
score = 0
total_num_of_qn = 3


counter +=1
tracker = 0

while tracker !=1:
  
  print("Q"+str(counter)+") "+ "What is in the mammalian digestive system?")
  print("   a) mouth")
  print("   b) liver")
  print("   c) pancrease")
  print("   d) gallbladder")
  answer = input("Your answer: ")
  answer = answer.lower()
  if answer == "a":
    output = "Correct."
    score -=1
  elif answer == "b":
    output = "Wrong."
    score -=1
  elif answer == "c":
    output = "Wrong."
    tracker =1
    score +=1
  elif answer == "d":
    output = "Wrong."
    score -=1
  else:
    output = "Please choose a, b, c or d only."
  
  print()
  print(output)
  print()
  print("Your current score: " + str(round((score/total_num_of_qn*100),1)) + "%"  )
  print()
  print()
  


counter +=1
tracker = 0

while tracker !=1:
  
  print("Q"+str(counter)+") "+ "What does the heart pump to the rest of the body?")
  print("   a) Oxygen")
  print("   b) Nitrogen")
  print("   c) Carbon monoxide")
  print("   d) Sulfur")
  answer = input("Your answer: ")
  answer = answer.lower()
  if answer == "a":
    output = "Correct."
    tracker =1
    score +=1
  elif answer == "b":
    output = "Wrong."
    score -=1
  elif answer == "c":
    output = "Wrong."
    score -=1
    
  elif answer == "d":
    output = "Wrong."
    score -=1
  else:
    output = "Please choose a, b, c or d only."

  print()
  print(output)
  print()
  print("Your current score: " + str(round((score/total_num_of_qn*100),1)) + "%"  )
  print()
  print()
  
  

counter +=1
tracker = 0

while tracker !=1:
  
  print("Q"+str(counter)+") "+ "Which has the strongest muscle?")
  print("   a) Right ventricle")
  print("   b) Right atrium")
  print("   c) Left atrium")
  print("   d) Left ventricle")
  answer = input("Your answer: ")
  answer = answer.lower()
  if answer == "a":
    output = "Wrong."
    score -=1
  elif answer == "b":
    output = "Wrong."
    score -=1
  elif answer == "c":
    output = "Wrong."
    score -=1
    
  elif answer == "d":
    output = "Correct."
    tracker =1
    score +=1
  else:
    output = "Please choose a, b, c or d only."

  

  print()
  print(output.lower())
  print()
  print("Your current score: " + str(round((score/total_num_of_qn*100),1)) + "%"  )
  print()
  print()
  
print("End of quiz!")
  
