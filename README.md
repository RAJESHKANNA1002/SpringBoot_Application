# SpringBoot_Application

@Entity
Every instance of an entity represents a row in the table.

@Id 
The @Id annotation is inherited from javax.persistence.Id, indicating the member field below is the primary key of the current entity. Hence your Hibernate and spring framework as well as you can do some reflect works based on this annotation. 

@GeneratedValue(strategy = GenerationType.IDENTITY)

this Annotation is used to create id for an Object auto Creation
