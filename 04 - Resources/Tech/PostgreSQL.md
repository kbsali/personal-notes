
```
-- -- available POLICY strategies -- --
(storage.foldername (name))[1] = auth.uid ()::text
(storage.foldername(name))[1] = 'public'
(storage.filename(name))[1] = 'only_uid.jpg'
(storage.extension(name))[1] = 'jpg'
name = 'folder/only_uid.jpg'
auth.uid() = 'd8c7bce9-cfeb-497b-bd61-e66ce2cbdaa2'
auth.uid () = owner AND (storage.foldername (name))[1] = auth.uid ()::text
right(auth.jwt() ->> 'email', 13) = '@blizzard.com'
```
