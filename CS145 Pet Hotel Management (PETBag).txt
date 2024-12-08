package com.pethotelproject;

public class Pet {

    private String petType;
    private String petName;
    private int petAge;
    private int dogSpace;
    private int daysStay;
    private double amountDue;

    public Pet() {
        petType = "none";
        petName = "none";
        petAge = 0;
        dogSpace = 0;
        daysStay = 0;
        amountDue = 0.0;
    }

    public Pet(String petType, String petName, int petAge, int dogSpace, int daysStay, double amountDue) {
        this.petType = petType;
        this.petName = petName;
        this.petAge = petAge;
        this.dogSpace = dogSpace;
        this.daysStay = daysStay;
        this.amountDue = amountDue;
    }

    // Getters and setters

    public String getPetType() {
        return petType;
    }

    public void setPetType(String petType) {
        this.petType = petType;
    }

    public String getPetName() {
        return petName;
    }

    public void setPetName(String petName) {
        this.petName = petName;
    }

    public int getPetAge() {
        return petAge;
    }

    public void setPetAge(int petAge) {
        this.petAge = petAge;
    }

    public int getDogSpace() {
        return dogSpace;
    }

    public void setDogSpace(int dogSpace) {
        this.dogSpace = dogSpace;
    }

    public int getDaysStay() {
        return daysStay;
    }

    public void setDaysStay(int daysStay) {
        this.daysStay = daysStay;
    }

    public double getAmountDue() {
        return amountDue;
    }

    public void setAmountDue(double amountDue) {
        this.amountDue = amountDue;
    }

    /* Implement the Pet objects behavior methods below */

    /*
     * Keep in mind that the methods signatures like: 
     * 
     * public static void checkIn(...)
     * 
     * will eventually have to change to something like: 
     * 
     * public boolean checkIn(...)
     * 
     * This will happen because another "driver" program
     * named something like "GlobalDriver.java", that has 
     * a public static void main(..) method in it, will 
     * actually be the one that instantiates (create) the 
     * Pet, Dog, and/or Cat objects from within it 
     * and then call the public Pet behavior methods. 
     * */ 
    
    public void checkIn() {
        // Implement check-in logic
    }

    public void checkout() {
        // Implement checkout logic
    }

    public void getPetInfo() {
        // Implement get pet information logic
    }

    public void createPet() {
        // Implement pet creation logic
    }

    public void updatePet() {
        // Implement pet update logic
    }
}
