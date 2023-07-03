# Health-Club-Management-System-And-Scheduling-Database
This is a Health Club Management System implemented using an AVL tree as the data structure to store and maintain the records of members and trainers. The system allows the owner of the health club to store member and trainer information, schedule slots for members based on their preferences, and perform various operations on the records.

# Functionalities
The system provides the following functionalities:

 1. Add_member() : Adds a new member to the system with the provided details. Member information is stored in the AVL tree based on their Member-ID.
 2. Add_trainer(): Adds a new trainer to the system with the provided details. Trainer information is stored in the AVL tree based on their Trainer-ID.
 3. Schedule_slot(): Assigns time slots to members based on their requested program, preferred time slot, and preferred trainer. The assignment is done on a first- come,first-serve basis. Members are assigned to trainers who can train for their preferred program. The function returns the list of assigned members and any non- 
 assigned members.
 4. Print_hour_wise_list(): Prints the hour/slot-wise list of members and trainers assigned grouped by every program. This provides a clear view of the schedule 
 for each program.
 5. Delete_member(): Deletes the record of a member with the specified Member-ID from the system.
 6. Delete_trainer(): Deletes the record of a trainer with the specified Trainer-ID from the system.
 7. Search_member(): Searches for a member record based on the specified key field and key value. It displays the complete record if found.
 8. Search_trainer(): Searches for a trainer record based on the specified key field and key value. It displays the complete record if found.
 9. Print_member_list(): Displays the records of all members stored in the system.
 10. Print_trainer_list(): Displays the records of all trainers stored in the system.
 11. Print_sorted_remuneration_list(): Displays the list of trainers in a sorted order according to their remuneration earned in a day, from highest to lowest.
 12. Print_intersection_list(): Takes a list of members (same as in Schedule_slot()) as input and returns a list of members who have been assigned their preferred 
 trainer.

# Data Structure
The system uses an AVL tree as the data structure to store and maintain the records of members and trainers. Each member and trainer record is represented as a node in the AVL tree. The AVL tree provides efficient insertion, deletion, and search operations while maintaining a balanced tree structure.

# Skills Used
1.Programming Language: C.
2.Data Structures: AVL TREE.
3.Algorithm design and implementation.
4.Sorting and searching techniques.
5.Menu-driven user interface.
6.Error handling and validation.
7.Problem-solving and logical thinking.
