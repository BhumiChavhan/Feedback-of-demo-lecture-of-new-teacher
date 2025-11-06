#include <stdio.h>

int main( ) {
    int content, delivery, clarity, interaction;
    float average;

    printf(" Demo Lecture Feedback\n");

    printf("Rate the following (1 = Poor, 5 = Excellent)\n");

    printf("1. Content quality: ");
    scanf("%d", &content);

    printf("2. Delivery (voice, confidence): ");
    scanf("%d", &delivery);

    printf("3. Clarity of explanation: ");
    scanf("%d", &clarity);

    printf("4. Interaction with students: ");
    scanf("%d", &interaction);

    // Calculate average rating
    average = (content + delivery + clarity + interaction) / 4.0;

    printf("\nFeedback Summary\n");
    printf("Average Rating: %f / 5\n", average);

    if (average >= 4.5){
        printf("Feedback: Excellent  teaching demo\n");
       }
       
    else if{
           (average >= 3.5)
            printf("Feedback: Very Good. Minor improvements suggested.\n");
          }

    else if {
              (average >= 2.5)
              printf("Feedback: Average. Needs more clarity and engagement.\n");
            }

    else{
        printf("Feedback: Below Average. Major improvements needed.\n");
       }

    printf("\n");
    
    return 0;
}

    

    return 0;
}
