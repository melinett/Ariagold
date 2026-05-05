alter table transactions add column if not exists price_per_gram bigint;
alter table transactions add column if not exists status text default 'pending';
