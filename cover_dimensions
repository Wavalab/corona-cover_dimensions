-- Returns dimensions for an image trying to cover a region
local function cover_dimensions(img_w, img_h, region_w, region_h)
  local ratio = img_w / img_h
  if ratio < region_w / region_h then
    return region_w, math.ceil(region_w / ratio)
  end
  return region_h, math.ceil(region_h * ratio)
end
