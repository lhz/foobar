.. code-block:: ruby

  class Foo < Bar
    def hello
      puts "hi!"
    end
  end

.. code-block:: bash

  $ ruby -r 'foo' -e 'foo = Foo.new; foo.hello'
