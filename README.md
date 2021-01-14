![Points badge](../../blob/badges/.github/badges/points.svg)

# Lab ## - Template

Template for Java labs

### Testing

To run the automated tests select the 'Shell' tab and enter the command `mvn test` to run the tests.

### Using Uploaded .jar Files

- Put the `.jar` files in the `./jars` directory.
- Set the run command to be `run = "export CLASSPATH=.:./jars/*; javac -d . *.java; java Main"`