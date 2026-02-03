----- a


// EXAMPLE: Robot moves 3 seconds forward, turns for 2 seconds, repeats
const unsigned long STEP1_FORWARD_TIME   = 3000;   // 3 seconds forward
const unsigned long STEP2_TURN_TIME      = 2000;   // 2 seconds turn
const unsigned long STEP3_FORWARD_TIME   = 3000;   // 3 seconds forward
const unsigned long STEP4_TURN_TIME      = 2000;   // 2 seconds turn
const unsigned long STEP5_FORWARD_TIME   = 3000;   // 3 seconds forward
const unsigned long STEP6_TURN_TIME      = 2000;   // 2 seconds turn


// EXAMPLE: Only move forward once, turn once, then repeat
const unsigned long STEP1_FORWARD_TIME   = 5000;   // 5 seconds forward
const unsigned long STEP2_TURN_TIME      = 1500;   // 1.5 seconds turn
const unsigned long STEP3_FORWARD_TIME   = 0;      // SKIP
const unsigned long STEP4_TURN_TIME      = 0;      // SKIP
const unsigned long STEP5_FORWARD_TIME   = 0;      // SKIP
const unsigned long STEP6_TURN_TIME      = 0;      // SKIP


// true = turn RIGHT, false = turn LEFT
const bool STEP2_TURN_RIGHT = true;    // Turn right
const bool STEP4_TURN_RIGHT = false;   // Turn left
const bool STEP6_TURN_RIGHT = true;    // Turn right

const int FORWARD_SPEED = 80;    // Increase for faster (max 255)
const int TURN_SPEED = 70;       // Adjust for tighter/wider turns
