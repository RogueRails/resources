# RSpec File Workflow

1. Create a RSpec file that maps to the implementation source file (ex: ` ./app/models/user.rb => ./spec/models/user_spec.rb`)
3. Duplicate the spec template below into the new spec file
2. Follow the guides at [betterspecs.org][betterspecs] to generate your expectations
 
#### RSpec Template

```ruby
require 'spec_helper'

describe {{ SUBJECT / CLASS }} do
  describe "# {{ INSTANCE METHOD NAME }} " do
    # Expectations...
  end

  describe ". {{ CLASS METHOD NAME }}" do
    # Expectations...
  end
end
```

  [betterspecs]: http://betterspecs.org