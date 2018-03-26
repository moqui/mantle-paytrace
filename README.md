# Mantle PayTrace Integration

Mantle payment processor integration for PayTrace API including level 2 and 3 data.

See API docs at: https://www.paytrace.net/developers/ 

To add this component to Moqui the easiest approach is to use the Gradle get component task:

    $ ./gradlew getComponent -Pcomponent=mantle-paytrace

Or add a dependency in your component.xml file like:

    <depends-on name="mantle-paytrace"/>

