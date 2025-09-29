# Develop-Java-Programs-Using-Autoboxing-Serialization-File-Handling
1. Autoboxing and Unboxing

👉 Autoboxing is the automatic conversion of a primitive data type into its corresponding wrapper class object.
👉 Unboxing is the reverse — automatically converting an object back into a primitive
Why it’s useful:

Makes code cleaner

Allows primitives to be used in collections (like ArrayList<Integer>) that work with objects only.
2. Serialization

👉 Serialization is the process of converting an object into a byte stream, so it can be saved to a file or sent over a network.
👉 Deserialization is the reverse — converting byte stream back to an object.

To make a class serializable, it must implement the java.io.Serializable interface.
Why it’s useful:

Saving object state permanently

Sending objects over network (e.g., in distributed systems)

🟦 3. File Handling

👉 File handling in Java allows reading from and writing to files using classes from java.io package.

File → represents file or directory path

FileWriter, BufferedWriter → write data

FileReader, BufferedReader → read data
✅ Why it’s useful:

Storing data persistently

Processing external data files

Creating logs or reports
