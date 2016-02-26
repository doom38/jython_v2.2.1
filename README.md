This fork aims to fix some unexpected behaviours on jython 2.2.1.
Sources come from [official mercurial repository ( tag: v2.2.1 )](https://hg.python.org/jython/rev/v2.2.1)

## Changes
 - **org.python.core.PyFloat.java** (line 673): Bug correction when comparing NaN values.
 - **org.python.core.PyString.java** (line 2032): Bug correction in to_bytes() method.
 - **org.python.parser.PythonGrammar.java** (line 7126): Comment unexpected exception in generated parser.