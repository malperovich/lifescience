================
SDK Installation
================

This example demonstrates how to install Indigo SDK to all supported languages.

----
Java
----

.. note::
	Indigo packages support Intel x86 and x64 platforms, and Windows, Linux, Mac OS X operating systems. If you need to use Indigo on other platforms, please contact us at lifescience.opensource@epam.com

If your project use Maven, you can add Indigo dependency to your pom.xml:


.. code-block:: xml

    <dependencies>
      ...
        <dependency>
            <groupId>com.epam.indigo</groupId>
            <artifactId>indigo</artifactId>
            <version>1.3.0beta.r16</version>
        </dependency>
        <dependency>
            <groupId>com.epam.indigo</groupId>
            <artifactId>indigo-inchi</artifactId>
            <version>1.3.0beta.r16</version>
        </dependency>
        <dependency>
            <groupId>com.epam.indigo</groupId>
            <artifactId>indigo-renderer</artifactId>
            <version>1.3.0beta.r16</version>
        </dependency>
        ...
    </dependencies>


On Debian starting from Wheezy and Ubuntu starting from 12.10 you can install stable version of Indigo SDK with the following command:

::

	sudo apt-get install libindigo-java

------
Python
------

On Debian starting from Wheezy and Ubuntu starting from 12.10 you can install stable version of Indigo SDK with the following-command:

::

	sudo apt-get install python-indigo

Otherwise you have to use one of this ways [#python]_:

- add path to content of Indigo archive to environment variable ``PYTHONPATH``.
- copy content of Indigo archive to folder ``site-packages`` in Python installation directory.
- copy content of Indigo archive to your project folder.
- append path to Indigo to ``sys.path``.

We also plan to add Indigo to Python Package Index.

----
.NET
----

To add Indigo assembly DLL to your Visual Studio project you need to [#dotnet]_:

1. Right-click the name of your project in **Solution Explorer** and then select **Add Reference**. A dialog should appear.
2. Select the **Browse** tab.
3. Browse to the folder that contains Indigo, select the **indigo-dotnet.dll** and **indigo-inchi-dotnet.dll**, **indigo-renderer-dotnet.dll** if you need, and then click **OK**.


**NuGet Repository**


Indigo .NET packages now available at `Nuget <https://www.nuget.org/packages/Indigo.Net/>`__

Just add ``Indigo.Net`` as a dependency into the project.



.. rubric:: Footnotes

.. [#python] http://docs.python.org/2/tutorial/modules.html#the-module-search-path
.. [#dotnet] http://msdn.microsoft.com/en-us/library/7314433t(v=vs.90).aspx
