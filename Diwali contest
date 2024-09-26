def max_problems_solved(N, P):
    # Total available time for solving problems (240 minutes minus travel time)
    remaining_time = 240 - P
    
    # Initialize counters for time and problems solved
    time_spent = 0
    count = 0
    
    # Iterate over problems from 1 to N
    for i in range(1, N + 1):
        # Time to solve the ith problem
        time_to_solve = 5 * i
        
        # Check if there's enough time left to solve this problem
        if time_spent + time_to_solve > remaining_time:
            break  # Max can't solve more problems
        
        # Update the time spent and count of problems solved
        time_spent += time_to_solve
        count += 1
    
    return count
N=int(input())
P=int(input())
result=max_problems_solved(N,P)
print(result)
