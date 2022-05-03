# Runner-Up-score
#Code to find final runner up score

no_of_player = int(input("Enter the total no. of player : "))

score = input("Enter scores (seperated by spaces): ")

score = score.split(" ")

new_list = [x for x in score[:no_of_player]]

Max = max(new_list)

while(max(new_list) == Max):
    new_list.remove(Max)

print("Runner Up Score", max(new_list))


# If anyone can solve this in more effective way, then please join me :-)
