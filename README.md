# Test Epicodus applications / Wufoo / Zapier / CRM flow

## Setup

Add to .env file:

`CLOSE_IO_API_KEY=insert_api_key_here`

## Testing application flow

1. Fill out application with every possibility:
`rspec spec/features/form_filler_spec.rb`

2. Wait a minute or more to be sure CRM entries have been created.

3. Test that applications have been created correctly in CRM. This also auto-deletes the entries after testing:
`rspec spec/features/test_applictions_spec.rb`
