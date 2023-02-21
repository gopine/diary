# February 21, 2023

Now trying to incorporate Server Actions to replace some of the API calls.

It works well with database mutation, but the revalidation logic is not very intuitive.

Have to manually clear the cache using `use server` and `revalidatePath`.