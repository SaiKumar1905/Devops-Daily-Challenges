Requirements:
Using the provided JSON file, implement the following:

Print a summary of each bucket: Name, region, size (in GB), and versioning status

Identify buckets larger than 80 GB from every region which are unused for 90+ days.

Generate a cost report: total s3 buckets cost grouped by region and department.

Highlight buckets with:
Size > 50 GB: Recommend cleanup operations.
Size > 100 GB and not accessed in 20+ days: Add these to a deletion queue.
4. Provide a final list of buckets to delete (from the deletion queue). For archival candidates, suggest moving to Glacier.
